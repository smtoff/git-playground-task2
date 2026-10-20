npm test 
Found a problem in lib/store.js where function matches only returns text matches when they exactly match - required to be any text which is included. Function changed to .include(text)
 
