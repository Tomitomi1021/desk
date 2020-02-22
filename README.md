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

### デスクID
	deskによって生成されたディレクトリには、以下のフォーマットからなるデスクIDがディレクトリ名として振られます。
	[0-9]*-[0-9]*-[0-9]*-[0-9]*
	一番初めの数字はディレクトリの生成年、その次の数字はに生成月、その次の数字は生成日、その次の数字は番号となります。
	番号は、後に生成されたものほど大きくなります。  
	<デスクID>と書かれている部分には、この値を指定するか、最新のディレクトリを0番目として、何番前かという指定のしかたができます。