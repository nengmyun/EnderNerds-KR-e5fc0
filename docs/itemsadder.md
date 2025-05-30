---
sidebar_position: 5
title: '🖼️ Items Adder'
---

import ReactPlayer from 'react-player'


# 🖼️ How to make Unlimited Adventures work with ItemsAdder

In order for the setup to work with ItemsAdder, you need to merge the resource pack with ItemsAdder.\
It's actually a very simple process. Please refer to the text guide and use the video as a supplement.


#### Step 1
> :red_circle: Stop your server.

#### Step 2
> ❌ Remove `resource-pack=` link from `server.properties`

#### Step 3
> :wrench: Find the `use_oraxen_or_itemsadder` setting in 📁`unlimited_adventures/AdventureCore/resource_pack` and set it to `true`

#### Step 4
> ❌ Remove 📁`modelengine` folder from the resource pack folder 📁`assets/modelengine` (it will be auto-generated by ItemsAdder)

#### Step 5
> Put Unlimited Adventures' resource pack into 📁`plugins/ItemsAdder/contents`

:::tip[Find your resource pack]
Don't know how to find your resource pack? Refer to [Resource Pack](resource-pack)
:::

#### Step 6
> Execute the `/iazip` command.

Done! Now start your server and enjoy Unlimited Adventures and ItemsAdder working together :heart:

:::warning
If you're installing ItemsAdder for the first time, please refer to its [guide](https://itemsadder.devs.beer/first-install).
:::


<ReactPlayer playing controls url="https://youtu.be/2nsQDgKO4oo"/>



### Other sources:

- [Items Adder Installation Guide](https://itemsadder.devs.beer/first-install) - you should read it if it's your first time using Items Adder.
- [Items Adder Resource Pack Merging Guide](https://itemsadder.devs.beer/plugin-usage/merge-resourcepacks) - essentially describes the same thing this guide describes.