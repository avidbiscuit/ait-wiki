---
title: Custom Mugs
type: docs
---

{{< callout type="warning" >}}
  You need to learn how texture pack and datapacks works!
{{< /callout >}}

---

## Create a Datapack
- Follow the tutorial on the [Minecraft Wiki on datapacks](https://minecraft.wiki/w/Data_pack) on how to set one up, use the namespace from earlier

- Create a new **.json** file in the path

> `data/(namespace)/drink/effect/(drink_name).json`

- Inside this new .json file, paste

> ```json
>{
>  "id": "(name:of_drink)",
>  "has_custom_color": true,
>  "custom_color": [0.49, 0.337, 0.337],
>  "potion_instances": [
>    {
>    "id": "minecraft:speed",
>    "duration": 340,
>    "amplifier": 2,
>    "ambient": false,
>    "show_particles": true,
>    "show_icon": true
>    }
>  ]
>}
> ```

- When replacing the **(name:of_drink)**, make sure that it is the same as the name of the `.json` file.

- For the custom color, make sure to use the; ISERT SILLY COLOR SYSTEM LOQOR USED HERE

- Now put this **datapack** into Minecraft.
