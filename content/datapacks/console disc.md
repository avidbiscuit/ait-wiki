---
title: Insert Disc Into Console
type: docs
---

{{< callout type="warning" >}}
  You need to learn how texture pack and datapacks works!
{{< /callout >}}

---

## Create a Datapack
- Follow the tutorial on the [Minecraft Wiki on datapacks](https://minecraft.wiki/w/Data_pack) on how to set one up, use the namespace from earlier


- Create a new **.json** file in the path

> `data/ait/tags/items/insertable_discs.json`

- Inside this new .json file, paste

> ```json
>{
>  "replace": false,
>  "values": [
>    "(name_space:disc_name)"
>  ]
>}
> ```

- Replace the **(name_space)** with one of the mod ID of the item.

- Replace **(disc_name)** with the name of the disc item.
