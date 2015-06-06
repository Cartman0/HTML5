# サブモジュールの追加

git submodule add \<git repository link\>

# サブモジュールの更新

## サブモジュールの更新(リモートの最新を追従する場合)

git submodule foreach git pull origin master

## サブモジュールの更新(git submodule init した時点での最新)

git submodule update

# サブモジュールの削除

git submodule deinit \<repository name\>

git rem -rf \<target file\>

# cloneするとき

git clone --recursive https://github.com/Cartman0/HTML5
