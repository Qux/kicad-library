# kicad-library
## パスの設定
`Preference` -> `Configure Paths...`に、以下の項目を追加する
| Name | Path |
| ---- | ---- |
| KIQUX | /Absolute/Path/To/this/library |

## ライブラリの設定
### シンボルライブラリ
1. `Preference` -> `Manage Symbol Library...`を開く
2. `Project Specific Libraries`に必要なものを追加する。  
    例: 
    | Nickname | Library Path |
    | ---- | ---- |
    | Switch_Qux | ${KIQUX}/quxsymbol/Switch_Qux.lib |

### フットプリントライブラリ
1. `Preference` -> `Manage Footprint Library...`を開く
2. `Project Specific Libraries`に以下を追加する。  
    | Nickname | Library Path |
    | ---- | ---- |
    | Qux_Footprint | ${KIQUX}/quxfootprint.pretty |