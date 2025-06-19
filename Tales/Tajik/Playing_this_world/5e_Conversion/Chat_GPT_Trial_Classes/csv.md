# csv 
Created Tuesday 13 May 2025

import pandas as pd

# Class list and maximum level
classes = ["Barbarian", "Bard", "Cleric", "Druid", "Fighter", "Monk", "Paladin", "Ranger", 
		   "Rogue", "Sorcerer", "Warlock", "Wizard"]
levels = list(range(1, 21))

# Feature Points gained per level
fp_gain_per_level = [3, 3, 4, 4, 5, 5, 6, 6, 7, 7, 8, 8, 9, 9, 10, 10, 11, 11, 12, 12]
total_fp_by_level = [sum(fp_gain_per_level[:i]) + 18 if i > 0 else 18 for i in range(20)]

# Create the data
data = [^]
for class_name in classes:
	for level, fp in zip(levels, total_fp_by_level):
		data.append({
			"Class": class_name,
			"Level": level,
			"Total Feature Points": fp
		})

# Create DataFrame
df = pd.DataFrame(data)

# Save as CSV
df.to_csv("dnd_feature_point_progression.csv", index=False)
print("CSV file created: dnd_feature_point_progression.csv")
