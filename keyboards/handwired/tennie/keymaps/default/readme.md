# Default keymap

This keymap is to serve as an example of how you could make a multi-layer keymap.

#### keymap

```
[base] = LAYOUT_kc(
//         ┌────────┬────────┬────────┐

              DEL   ,  SPC   ,   ENT  ,

//    ├────────┼────────┼────────┼────────┼

        LEFT   ,  DOWN  ,   UP   ,  RGHT ,

//    ├────────┼────────┼────────┼────────┼

              SHRK  ,  OGRE  ,   TCP

//         └────────┴────────┴────────┘
),
[shrek] = LAYOUT_kc(
//         ┌────────┬────────┬────────┐

              MPRV  ,  MPLY  ,  MNXT  ,

//    ├────────┼────────┼────────┼────────┼

         BRID  ,  VOLD  ,  VOLU  ,  BRIU  ,

//    ├────────┼────────┼────────┼────────┼

             _______, _______, _______

//         └────────┴────────┴────────┘
),
[ogre] = LAYOUT_kc(
//         ┌────────┬────────┬────────┐

             RGB_MOD, RGB_TOG, RGB_RMOD

//    ├────────┼────────┼────────┼────────┼

         F13   ,   F14  ,   F15  ,  F16   ,

//    ├────────┼────────┼────────┼────────┼

             _______, _______, _______

//         └────────┴────────┴────────┘
),
[tcp] = LAYOUT_kc(
//         ┌────────┬────────┬────────┐

              WBAK  ,  WREF  ,  WFWD  ,

//    ├────────┼────────┼────────┼────────┼

       XXXXXXX ,  PGDN  ,  PGUP  , XXXXXXX ,

//    ├────────┼────────┼────────┼────────┼

             _______, _______, _______

//         └────────┴────────┴────────┘
),
```
