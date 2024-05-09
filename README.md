# preferred_lang_updater
a small script for updating the preferred_language facet of a user in Alma. Asyncronous, capped at 45 simultaneous coroutines

1. Open in colab.google.com
2. Create an .env file in your project home directory. type in `usersKey=yourapikeyhere`. Must have r/w permissions.
3. Upload a file containing the list of user Id's in a column titled `id`
4. Ensure the preferred_language code and description are correct. It is already formatted for Spanish `value: 'es', desc: "Spanish"`
