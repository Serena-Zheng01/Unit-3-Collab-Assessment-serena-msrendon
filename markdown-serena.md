Welcome to **TreeLife**, your guide to learning everything about the beauty, diversity, and importance of trees around the world.

---

## About Us

At **TreeLife**, we're passionate about forests and green living.

Our mission is to:

- Educate people about the different types of trees
- Promote sustainable forestry
- Encourage reforestation projects

> "The best time to plant a tree was 20 years ago. The second best time is now."
 — *Chinese Proverb*
---

## Featured Trees

### Oak Tree
**Scientific Name:** *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.

![image of oak tree](https://blog.davey.com/media/ymlb2hok/oak-tree-fall-foliage.jpg?rxy=0.39730150972736855,0.3151383322236556&width=430&height=282&v=1da0289f6732f90&format=webp&quality=80)

---

### Pine tree

**Scientific name:** *Pinus*

Evergreen amd aromatic, pine trees thrive in colder regions.

![image of pine tree](https://m.media-amazon.com/images/I/91SV1BcZv7L.jpg)

---

## Tree Identification Tool

You can use this simple **Javascript** function to indentify a tree by its characteristics:

```
function identify_tree(leaf_shape, region){
    if(leaf_shape == "needle" && region == "cold"){
        return "Pine Tree"
        } else if(leaf_shape == "broad" && region == "cold") {
            return "Oak Tree"
            else {
                return "Unknown Tree"
                }
}
console.log(identify_tree("needle", "cold")
```