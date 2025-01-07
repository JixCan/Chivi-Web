# Chivi-Web
Web tool for better memorizing new chinese words

TODO:
- login/signup form
- adding/removing kanjipacks to local dictionary
- export dictionary
- show dictionary
- import HSK levels dictionary
- training tool
- find any word from database

Possible stack？
- React + Vite + TS?; DB: sqlite?

Possible DB schema:
- user: id, username, password, 
- kanjipack: id, character, pinyin, transslation
- user_kpacks: id, userid, kpackid
- user_defined_translations: id, userid, kpackid, translation
