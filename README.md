♯keymapnum
RC(0)  RC(1)  RC(2)  RC(3)  RC(4)                     RC(5) RC(6)  RC(7)  RC(8)  RC(9)
RC(10) RC(11) RC(12) RC(13) RC(14) RC(15)     RC(16) RC(17) RC(18) RC(19) RC(20) RC(21)
RC(22) RC(23) RC(24) RC(25) RC(26) RC(27)     RC(28) RC(29) RC(30) RC(31) RC(32) RC(33)
RC(34) RC(35) RC(36) RC(37) RC(38) RC(39)     RC(40) RC(41)                      RC(42)  

♯layer
layer0-base sensor:
layer1-mouse sensor:aml
layer2-toggle mouse sensor:mouse toggle
layer3-base2 sensor:
layer4-number sensor:
layer5-func sensor:
layer6-arrow sensor:RLarrow
layer7-UNIQ sensor:
layer8-scroll sensor:scroll
layer9-MOUSE-SLOW sensor:snipe

#seting
jis:roba.keymap
// OS設定を日本語キーボードのまま使用するための変換定義

#define JP_DQUOTE       AT                // "
#define JP_AMPERSAND    CARET             // &
#define JP_QUOTE        AMPERSAND         // '
#define JP_EQUAL        UNDER             // =
#define JP_CARET        EQUAL             // ^
#define JP_YEN          0x89              // ¥
#define JP_PLUS         COLON             // +
#define JP_TILDE        PLUS              // ~
#define JP_PIPE         LS(0x89)          // |
#define JP_AT           LEFT_BRACKET      // @
#define JP_COLON        SINGLE_QUOTE      // :
#define JP_ASTERISK     DOUBLE_QUOTES     // *
#define JP_BACKQUOTE    LEFT_BRACE        // `
#define JP_UNDERSCORE   LS(0x87)          // _
#define JP_LBRACKET     RIGHT_BRACKET     // [
#define JP_RBRACKET     BACKSLASH         // ]
#define JP_LPAREN       ASTERISK          // (
#define JP_RPAREN       LEFT_PARENTHESIS  // )
#define JP_LBRACE       RIGHT_BRACE       // {
#define JP_RBRACE       PIPE              // }
#define JP_KANA         LANGUAGE_1        // かな
#define JP_EISU         LANGUAGE_2        // 英数
#define JP_HANZEN       GRAVE             // 半角/全角
#define JP_DOLLAR       DOLLAR             // $
