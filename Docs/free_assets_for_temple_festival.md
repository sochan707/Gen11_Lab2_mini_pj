# Complete asset checklist for the temple festival map

Checked 27 October 2026. Sources for downloadable recommendations: **Poly Pizza** and **Unity Asset Store** only. This is a checklist for the visual map in [temple_festival_map_ideas.md](temple_festival_map_ideas.md), followed by optional assets for making it a playable game. Nothing has been downloaded or imported into Unity.

## 1. Assets already in the project

| Map part | Existing asset | What it can cover |
| --- | --- | --- |
| Destination | `Assets/Resources/Pagoda.obj` and `Assets/Textures/T_Temple.jpg` | Temple landmark |
| Entrance | `Assets/Models/gate.obj` | Gate silhouette; check whether its cultural style fits your chosen temple |
| Final approach | `Assets/Resources/SM_StairCase_02.obj` | Main steps |
| Landscape | `Assets/Resources/RS_Mountain 1.obj`, `RS_Mountain 2.obj`, `Assets/Models/Ground.prefab`, and grass texture/material | Hills, backdrop, and base ground |

## 2. Download for the full *visual* map

These five Poly Pizza downloads cover most missing models. The bundle pages mark them free and CC0 and provide FBX and GLB/GLTF formats. Pick individual models from the bundles; you do not need to use every object.

| Missing element | Recommended free asset | Place it here |
| --- | --- | --- |
| 4–6 stalls, cart, benches, crates/bags, fence, cooking smoke or fire | [Medieval Village Pack](https://poly.pizza/bundle/Medieval-Village-Pack-NsHhjhlrfY) | Food street and plaza edges. Use its Market Stand, Cart, Bench, Crate, Fence, Bonfire and Smoke selectively. Its fantasy/medieval buildings may not suit the temple. |
| Food, drinks, plates, cooking utensils | [Ultimate Food Pack](https://poly.pizza/bundle/Ultimate-Food-Pack-h3WC1gyRb4) | Give each stall a different display. The pack has fruit, sweets, drinks, cooking pot, frying pan, chopsticks, corndog and more. |
| Trees, bushes, flowers, rocks, stepping stones and paving pieces | [Stylized Nature MegaKit](https://poly.pizza/bundle/Stylized-Nature-MegaKit-T34GZFA0fm) | Garden, pond edge, lantern path and temple courtyard. Includes rock path pieces. |
| Lantern model | [Hanging Lantern](https://poly.pizza/m/3jzk3YShv1) | Food street and side path; repeat it at even intervals. |
| Welcome sign and stall labels | [Sign](https://poly.pizza/m/Kg1kxfrItG) | Entrance and stalls. You still need to add your own lettering in Unity. |

**If you prefer Unity Asset Store packs:** [Food FREE](https://assetstore.unity.com/packages/3d/props/food/food-free-low-poly-3d-models-pack-260726) can replace the food bundle, and [3D Low Poly Nature Packs Free](https://assetstore.unity.com/packages/3d/environments/landscapes/3d-low-poly-nature-packs-free-327057) can replace the nature bundle. The store listings show them as free with the Standard Unity Asset Store EULA. Check how their style looks beside your pagoda before committing to a full scene.

## 3. Make with Unity's basic tools; no asset download required

| Element | Simple build approach |
| --- | --- |
| Main street, plaza and courtyard base | Terrain or flat planes with different materials; use the rock path pieces for a more detailed temple approach. |
| Pond surface | A blue/green plane, with rocks and plants around its border. |
| Performance platform | A few cubes/planes; leave the plaza center open if you prefer a lantern display instead. |
| Stall fabric color and temple/festival color zones | Materials on the downloaded meshes and existing geometry. |
| Lantern glow and moonlight | Unity lights; the lantern mesh alone will not light the path. |
| Text on signs and simple map board | Unity UI/TextMeshPro or a texture you create. The Sign download supplies only a sign model. |
| Steam, drifting particles, fireflies | Unity particle system if desired; the Medieval Village pack also has a smoke model. |

## 4. Optional, depending on your gameplay

| If you want… | You may need… | Free source |
| --- | --- | --- |
| Walking around as a player | Character controller, camera and player model | [First Person + Third Person Character Controllers](https://assetstore.unity.com/packages/3d/characters/first-person-third-person-character-controllers-196526) from Unity. Its current listing says free and URP compatible for Unity 6000.3.0f1; check its non-standard EULA. |
| Festival visitors or stall vendors | Character models, animations and simple NPC behavior | [City People FREE Samples](https://assetstore.unity.com/packages/3d/characters/city-people-free-samples-260446) supplies character samples. You would still set up motion/behavior yourself. |
| Food stamp trail or hidden discovery | Collectible model, interaction logic, counter and UI | A [Poly Pizza Coin](https://poly.pizza/m/QHZtj94fvh) can stand in for a token. The interaction and UI are game systems you build; no asset pack is required. |
| Ambient crowd/garden sound | Audio clips and AudioSources | [Free General Ambience Sounds](https://assetstore.unity.com/packages/audio/ambient/urban/free-general-ambience-sounds-246000) includes crowd and nature recordings, but is large (about 1.5 GB). |
| More elaborate pond water | A water shader/material | [A.U.R.W. URP Free](https://assetstore.unity.com/packages/vfx/shaders/a-u-r-w-urp-free-195139) is optional; a colored plane is enough to begin. |

## Area-by-area check before you build

- **Entrance:** existing gate + sign model + text/map board.
- **Food street:** 4–6 stalls + food/drinks + benches/cart/crates + path + lanterns.
- **Plaza:** open walking space + simple performance platform or lantern display + edge seating.
- **Garden and pond:** trees/bushes/rocks + pond plane + stepping stones.
- **Lantern path:** rock path or ground material + repeated lantern models + Unity lights.
- **Courtyard:** existing stairs + paving + sparse plants/rocks + temple view.
- **Temple:** existing pagoda, temple texture, and one interaction or viewpoint if the game needs an ending.

**Smallest complete visual download set:** Medieval Village Pack, Ultimate Food Pack, Stylized Nature MegaKit, Hanging Lantern, and Sign. Your existing project assets plus Unity's basic geometry, materials and lights cover the rest of the visual map. NPCs, sound and a controller are separate choices for a playable festival.

## Style and licenses

- Choose one architectural reference before decorating. The existing gate appears torii-like; for a Khmer/Cambodian temple theme, avoid Japanese-specific gates and lanterns unless the mix is intentional.
- Poly Pizza sets licensing per item. The five recommended Poly Pizza pages above are marked **CC0**; check each download page again when downloading.
- Free Unity Asset Store assets are not automatically CC0. Follow each listing's EULA and check its Unity/URP compatibility before importing.
