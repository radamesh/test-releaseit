# test-releaseit

npm init -y

npm install release-it @release-it/conventional-changelog @commitlint/config-conventional @commitlint/cli --include=dev

yarn add release-it @release-it/conventional-changelog @commitlint/config-conventional @commitlint/cli --include=dev

npm isntall husky --include=dev

yarn add  husky --include=dev

./node_modules/husky/lib/bin.js install

touch .husky/commit-msg && chmod a+x .husky/commit-msg

git commit -a

run release