---
title: Custom Unlockable Dimensions
type: docs
---

{{< callout type="warning" >}}
  You need to learn how texture pack and datapacks works!
{{< /callout >}}

---

## Create a Datapack
- Follow the tutorial on the [Minecraft Wiki on datapacks](https://minecraft.wiki/w/Data_pack) on how to set one up, use the namespace from earlier

- You can lock any dimension from any mod, or even vanilla minecraft.

- Create a new **.json** file in the path

> `data/(namespace)/locked_dimension/(dimension_name).json`

- Inside this new .json file, paste

> ```json
>{
>  "dimension": "(dimension:id)",
>  "stack": "(google item stack codec)"
>}
> ```

- Replace the **(dimension:id)** with the name and mod id for the dimension you want locking.

- Now put this **datapack** into Minecraft.

