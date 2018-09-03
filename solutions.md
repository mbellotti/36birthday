# Puzzles Solutions

## 001 "Just call me Jack"
You have three Japanese kanji characters 安 (yasu) 楽 (raku) 死 (shi) along with the pronunciations used for their individual meanings as stand alone words. The fun thing about kanji, though, you can combine characters to create words with completely different pronunciations and sometimes surprising meanings. To solve this puzzle you had to figure out the proper arrangement of the characters.

安楽死 is a favorite vocabulary word of Japanese 101 teachers because its meaning is not immediately obvious from the individual characters it illustrates some of the complexities of kanji. It translates to euthanasia, the red cross and the title of the in the puzzle are further hints. The solution is: KEVORKIAN

## 002 The order is the index
You have a list of USDS's six core values, except one word is off in each one. In solve this puzzle you have to figure out which word is wrong then (as the title suggests) use the value number as an index to highlight a letter. That will spell out the answer to the riddle. The solution is: CANDOR

## 003 Cats love bacon
If you happened to view source on the website you're directed to, you'll noticed that the two different pictures of the cat are called "A" and "B". The Bacon in the title refers to Sir Francis Bacon who (among other things) invented the Bacon cipher, in which letters are encoded with combinations of A and B. Decode the message and it should read: "TITLEOFDEUSLOUEBACONTALK" Devs Love Bacon was a 2014 conference in London I spoke at. The title of that talk (and also the solution) was: HACK TOGETHER!

## 004 Or is there?
Finally a puzzle solved by viewing the source! The attribute in the body should tell you that the Base64 string is encrypted using AES-ECB, all you need to do is figure out the 32 bit secret key. You know what's 32 bits? The phrase "4 is unlucky, so no puzzle four." You can decrypt the message to plain text using an online tool like https://www.devglan.com/online-tools/aes-encryption-decryption When decrypted the answer is GIRAFFE

## 005 The Pantone Cipher
Series of color blocks form a cipher. As the title of this puzzle suggests you have to match the color to its pantone code. This is tricky but can be done by exploring Pantone's color finder profiles. Converters like https://codebeautify.org/hex-to-pantone-converter might help you narrow the search, but don't have all the available pantone colors. If you're able to successfully decode the colors you'll have the following series of numbers:

8122 5025 152 105 2251 8085 118 402 8502 315 126 318 250 201 502 8502 122 150 315 181 413 151 514

From there it's a A1Z26 decryption (where A=1, B=2, etc). The tricky part is figuring out whether something like 26 is Z or BF. When you've successfully decoded it the message reads:

"Have you ever heard the wolf cry to the blue corn moon"

Which of course is the chorus of colors of the wind from POCAHONTAS

## 006 Stand By for Text Transmission
The firt part of the puzzle is a sudoku. When completely filled out the blue boxes highlight ten digits 4342772974. This is a phone numnber. When you call this number you get a snarky answering message for Space Force but when you text this number you get a random space fact. If you kept texting this number you will eventually get asked "What is the combination on my luggage?" Which is of cource a reference to the legendary comedy Space Bellls. Answer back "12345" and it will reply "The answer you're looking for is the same kind of jam they jammed our radar with. Damn that Lone Star!" therefore the correct answer is: RASPBERRY

## 007 Let's Go Rangers
This is a Zebra puzzle with a twist, the people in it are real people. The puzzle isn't solvable until you've looked them up and know their nationalities and their positions. After which it should be obvious that 160lb soaking wet Petr Prucha is playing defense when he should be a forward. The solution: BACKMAN PRUCHA

## 008 Boredom Points
At the website (https://www.tripline.net/bellmar/) there are routes for three trips from different parts of my life. First task is identifying the airport codes for each stop of the trip:

- JFK -> DET -> KIX
- PRG -> STN -> CMN -> ACC
- KEF -> LGW -> SXF

Then find the longest anagram using letters from the route. In the case of a tie, the word with the highest Scrabble score is the correct one. The last challenge is to make sure you have the trips in the right order. I went to Japan first, then Prague/Ghana, then Berlin. So the solution is: FIXED CRAMPS FLEW

## 009 Boat flipping
The secret image in the Magic Eye is not seen by unfocusing your eyes, but rather by getting into the image's alpha channel.  Steganography FTW! The secret message looks like this:

~~~~
      c~~p ,---------.
 ,---'oo  )           \
( O O                  )/
 `=^='                 /
       \    ,     .   /
       \\  |-----'|  /
       ||__|    |_|__|
	   
What's my score?
https://www.youtube.com/watch?v=PcoowIQBYAg

~~~~

It's a picture of a hipo and a link to a youtube video of the classic video game Ducks Ahoy! You have to watch the video and count how many times the hipo flips over the boat giving you the solution of: TWO

## 010 Debugging
The program is written in TLA+ you have to figure out enough of its syntax to understand that the program takes two lists of single character strings, checks to see if letters from one are present in the other and filters so only unique characters remain. This spells out scutigera coleoptrata or as it is more commonly known: HOUSE CENTIPEDE

## 011 Who's going to build the disco?
The puzzle pieces when correctly assembled form a QR code. If scanned with your phone it reveals the following text: "Back in the day as we learned a man was not considered to be fully grown had he not gonna beyond the hills, had he not crossed the 7 seas. Yeah, 7 seas at least" Googling this text should bring up the song it comes from (one of my favorites) Gogol Bordello's Wonderlust King. Also in the lyrics? The answer to the question asked in the title and the solution to this puzzle: THE CHINESE

## 012 Binge Watching
This is a list of rebus puzzles using emojis. Each one is the name of a series I've binged watched over the last year.

(👶+lon)(🍔-ger)(📈-e) BabylonBerlin
🎭🚗☕️ ComediansinCarsGettingCoffee
(🐰-e)(🔒-ck)+ts Harlots
👸🏿🍬 QueenSugar
(🥦-ccoli)➕💒 Broadchurch
(👺-k)(🖥-compu)𝟎 MasterofNone

When filled out correctly the spell out the solution: BARQUE

## 013 Because there had to be a COBOL one
The songs create a timeline that corresponds to each language's creation.

LISP 1956 Heartbreak Hotel
COBOL 1959 The Battle of New Orleans
Forth 1968 Hey Jude
Prolog 1972 The First Time Ever I Saw Your Face
Ada 1980 Call Me
Objective-C 1983 Every Breath You Take
Erlang 1986 That's What Friends Are For
Python 1989 Look Away
Java 1995 Gangsta's Paradise
OCaml 1996 Macarena
Clojure 2007 Irreplaceble
Elm 2012 Somebody That I Used to Know
Cuneiform 2013 Thrift Shop
hack 2014 Happy

Therefore the correct answer is: YEARS
