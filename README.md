# desk
## インストール方法
deskをパスの通るところに置いてください。
## 依存するもの
userinfo -> 次のURLにあります。 https://github.com/Tomitomi1021/userinfo
## 使用方法
### フォーマット
  desk <コマンド> [<引数>]  

### コマンド一覧

#### make
	desk make
	新しいデスクを作成します。  

#### enter
	desk enter [<デスクID>]
	カレントディレクトリをデスクに移動します。  
	デスクID: 移動先のデスクID、省略した場合は最新のデスク。

#### view
	desk view [<デスクID>]
	デスクを閲覧します。  
	デスクID: 閲覧対象のデスクID、省略した場合は最新のデスク。

#### link
	desk view [<デスクID>] <リンク名>
	デスクへのリンクを貼ります。  
	デスクID: リンク先のデスクID、省略した場合は最新のデスク。
	リンク名: デスクへのリンクの名前。

#### list
	desk list
	デスクの一覧を表示します。  
