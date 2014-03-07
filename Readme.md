###Bug-fix patch for [dresende/node-orm2](https://github.com/dresende/node-orm2) v2.1.3

##Details

Mysql only

Using "unique: true" causes "ER_DUP_KEYNAME" on sync > [here](https://github.com/dresende/node-orm2/issues/326)

##Installation

	npm install orm-2.1.3