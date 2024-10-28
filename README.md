  "key_binder/bindings":
    - {accept: 0, send: Page_Up, when: has_menu}
    - {accept: minus, send: Page_Down, when: has_menu}
    - {accept: Return, send: space, when: has_menu}

  翻頁：0為PageUp，-為PageDown
  Enter可輸出選中的字  
  翻頁：0為PageUp，-為PageDown
  Enter可輸出選中的字
  
  "menu/page_size": 9

  調整候選字單頁9個
  
  "engine/translator/preedit_format": SPOT
  
  候選字會因為用字次數改變，越常用的字會排越前面
