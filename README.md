# mk-sample-embedded-app
shopify test app

こちらに沿って進めます
https://shopify.dev/tutorials/build-a-shopify-app-with-node-and-react?shpxid=dbef977c-BFC9-4DF2-7F4E-C0D0545387FF

参考
https://www.shopify.jp/blog/partner-shopify-app-development

ディレクトリ直下に.env　を作成
SHOPIFY_API_KEY='｛ApiKey｝'
SHOPIFY_API_SECRET='｛ApiSecret｝'
SHOPIFY_API_SCOPES=read_products
SHOPIFY_APP_URL='｛AppUrl ex:https://XXXX.ngrok.io｝'

npm install
npm install ngrok -g

npm run dev
別窓で
ngrok http 3000

でngrokのURLが発行されるのでShopifyのアプリ画面の設定（2か所）と.envを書き換える
