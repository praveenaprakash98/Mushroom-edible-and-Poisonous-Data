# Mushroom-edible-and-Poisonous-Data

EDA on Mushroom-edible-and-Poisonous-Data

“This EDA analysis is licensed under Apache 2.0 License.” “Users must provide proper attribution to Praveena Prakash before using this work.” "Praveena Prakash, EDA on Mushroom-edible-and-Poisonous-Data
 , Github, 2025." Ref:https://github.com/praveenaprakash98/Mushroom-edible-and-Poisonous-Data

 # Data Schema

 Column 1: class

* Description: Edibility classification
* Values: e = edible, p = poisonous

Column 2: cap-shape

* Description: Shape of the mushroom cap
* Values: b = bell, c = conical, x = convex, f = flat, k = knobbed, s = sunken

Column 3: cap-surface

* Description: Surface texture of the cap
* Values: f = fibrous, g = grooves, y = scaly, s = smooth

Column 4: cap-color

* Description: Color of the mushroom cap
* Values: n = brown, b = buff, c = cinnamon, g = gray, r = green, p = pink, u = purple, e = red, w = white, y = yellow

Column 5: bruises

* Description: Whether the mushroom bruises when touched
* Values: t = bruises, f = no bruises

Column 6: odor

* Description: Smell of the mushroom
* Values: a = almond, l = anise, c = creosote, y = fishy, f = foul, m = musty, n = none, p = pungent, s = spicy

Column 7: gill-attachment

* Description: How gills are attached to the stalk
* Values: a = attached, d = descending, f = free, n = notched

Column 8: gill-spacing

* Description: Spacing between gills
* Values: c = close, w = crowded, d = distant

Column 9: gill-size

* Description: Width of the gills
* Values: b = broad, n = narrow

Column 10: gill-color

* Description: Color of the gills
* Values: k = black, n = brown, b = buff, h = chocolate, g = gray, r = green, o = orange, p = pink, u = purple, e = red, w = white, y = yellow

Column 11: stalk-shape

* Description: Shape of the stalk
* Values: e = enlarging, t = tapering

Column 12: stalk-root

* Description: Root structure of the stalk
* Values: b = bulbous, c = club, u = cup, e = equal, z = rhizomorphs, r = rooted, ? = missing

Column 13: stalk-surface-above-ring

* Description: Surface texture of stalk above the ring
* Values: f = fibrous, y = scaly, k = silky, s = smooth

Column 14: stalk-surface-below-ring

* Description: Surface texture of stalk below the ring
* Values: f = fibrous, y = scaly, k = silky, s = smooth

Column 15: stalk-color-above-ring

* Description: Color of stalk above the ring
* Values: n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow

Column 16: stalk-color-below-ring

* Description: Color of stalk below the ring
* Values: n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow

Column 17: veil-type

* Description: Type of veil
* Values: p = partial, u = universal

Column 18: veil-color

* Description: Color of the veil
* Values: n = brown, o = orange, w = white, y = yellow

Column 19: ring-number

* Description: Number of rings on the stalk
* Values: n = none, o = one, t = two

Column 20: ring-type

* Description: Type of ring
* Values: c = cobwebby, e = evanescent, f = flaring, l = large, n = none, p = pendant, s = sheathing, z = zone

Column 21: spore-print-color

* Description: Color of spore print
* Values: k = black, n = brown, b = buff, h = chocolate, r = green, o = orange, u = purple, w = white, y = yellow

Column 22: population

* Description: Population density where found
* Values: a = abundant, c = clustered, n = numerous, s = scattered, v = several, y = solitary

Column 23: habitat

* Description: Natural habitat where mushroom grows
* Values: g = grasses, l = leaves, m = meadows, p = paths, u = urban, w = waste, d = woods

Dataset Summary:

* Total Records: 8,124 mushrooms
* Total Features: 23 columns
* Data Type: All categorical features (encoded as single characters)
* Target Variable: 'class' (edible vs poisonous)

Dataset From : Kaggle (https://www.kaggle.com/datasets/uciml/mushroom-classification)
