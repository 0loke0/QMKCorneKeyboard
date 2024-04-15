#Mapkeys

Esta configuración contiene 5 capas, las cuales están hechas con el objetivo de facilitar el uso del teclado, implementando una distribución intuitiva y ergonómica.

##Capa QWERTY

//|-----------------------------------------------------|                    |-----------------------------------------------------|
     KC_ESC,  KC_Q,    KC_W,    KC_E,    KC_R,    KC_T,                         KC_Y,    KC_U,    KC_I,    KC_O,    KC_P,    KC_BSPC,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
  TD(TD_CAPLOCK), KC_A, KC_S,   KC_D,    KC_F,    KC_G,                         KC_H,    KC_J,    KC_K,    KC_L,    KC_SCLN, KC_QUOT,
  //---------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_LCTL, KC_Z,    KC_X,    KC_C,    KC_V,    KC_B,                         KC_N,    KC_M,    KC_COMM, KC_DOT,  KC_SLSH, RSFT_T(KC_ENT),
  //---------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                         KC_LCTL, LOWER, KC_SPC,        KC_LGUI, RAISE, KC_RALT
                                      //|--------------------------|  |--------------------------|

##Capa LOWER

  //|-----------------------------------------------------|                    |-----------------------------------------------------|
    KC_ESC,   KC_F1  , KC_F2  , KC_F3  , KC_F4  , KC_F5  ,                      KC_7,    KC_8,    KC_9,    XXXXXXX, XXXXXXX,  KC_BSPC,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_TAB,  KC_F6  , KC_F7  , KC_F8  , KC_F9  , KC_F10 ,                      KC_4 ,   KC_5,    KC_6,    XXXXXXX,  KC_UP,   KC_DEL,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_LSFT, KC_LCTL, ARROWS, ARROWS, KC_F11 , KC_F12 ,                       KC_1 ,   KC_2,    KC_3,    KC_LEFT,  KC_DOWN, KC_RGHT,
  //|--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                        KC_LCTL, KC_TRNS, ARROWS,       KC_0, KC_DOT, KC_RALT
                                      //|--------------------------|  |--------------------------|

##Capa RAISE

//|-----------------------------------------------------|                    |-----------------------------------------------------|0
     KC_GRV, KC_EXLM, KC_AT,   KC_HASH, KC_DLR,  KC_PERC,                      KC_CIRC, KC_AMPR, KC_ASTR, KC_LPRN, KC_RPRN, KC_BSPC,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_TAB, XXXXXXX, XXXXXXX, XXXXXXX, KC_NUBS, KC_MINUS,                     KC_PLUS, KC_EQL, KC_PSLS, KC_LCBR, KC_RCBR, KC_DEL,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_LSFT, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      KC_PSCR, XXXXXXX, KC_UNDS, KC_LBRC, KC_RBRC, RSFT_T(KC_ENT),
  //|--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                          KC_LGUI, LOWER, KC_SPC,    KC_SPC, KC_TRNS, KC_RALT
                                      //|--------------------------|  |--------------------------|
##Capa ADJUST

  //|-----------------------------------------------------|                    |-----------------------------------------------------|
     XXXXXXX, XXXXXXX,  XXXXXXX, XXXXXXX, XXXXXXX, RGB_TOG,                      XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     XXXXXXX, RGB_HUI, RGB_SAI, RGB_VAI, RGB_SPI, RGB_MOD,                       XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     XXXXXXX, RGB_HUD, RGB_SAD, RGB_VAD, RGB_SPD, XXXXXXX,                       XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,
  //|--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                         KC_LCTL, KC_TRNS, KC_SPC,    KC_SPC, KC_TRNS, KC_RALT 
                                      //|--------------------------|  |--------------------------|

##Capa ARROWS

[_ARROWS] = LAYOUT(
  //|-----------------------------------------------------|                    |-----------------------------------------------------|
    KC_ESC,   XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      KC_BTN3, XXXXXXX, KC_MS_U, KC_BTN2, XXXXXXX, KC_WH_U,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
     KC_TAB,  KC_BTN1, KC_BTN3, KC_BTN2, XXXXXXX, XXXXXXX,                      KC_BTN5, KC_MS_L, KC_MS_D, KC_MS_R, KC_PGUP, KC_WH_D,
  //|--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
    KC_LSFT, KC_LSFT,  KC_TRNS, KC_TRNS, XXXXXXX, XXXXXXX,                      KC_BTN4, XXXXXXX, XXXXXXX, KC_HOME, KC_PGDN, KC_END,
  //|--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                         XXXXXXX, KC_TRNS, KC_TRNS,    KC_BTN1, XXXXXXX, KC_RALT
                                      //|--------------------------|  |--------------------------|
  )

                                      
