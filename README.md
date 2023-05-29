# TorahBibleCodes
Torah Bible Codes - Open-Source Python

HOMEPAGE URL: https://TorahBibleCodes.com
<br />
https://www.TorahBibleCodes.com
<br />
GITHUB: @TorahBibleCodes https://github.com/torahbiblecodes
<br />
READ THE DOCS: @TorahBibleCodes https://torahbiblecodes-sphinx.readthedocs.io/en/latest/index.html
<br />
STACKOVERFLOW: @TorahBibleCodes https://stackoverflow.com/users/8911652/torahbiblecodes
<br />
TWITTER: @TorahBibleCodes https://twitter.com/TorahBibleCodes
<br />
YOUTUBE: @TorahBibleCodes https://www.youtube.com/@TorahBibleCodes
<br />
YOUTUBE: @TorahBibleCodes https://www.youtube.com/channel/UCNsvtMx4JJRpNzzPq57HCqg
<br />
GIVESENDGO: @TorahBibleCodes https://www.givesendgo.com/torahbiblecodes

# Known Bugs and Open Issues
https://github.com/TorahBibleCodes/TorahBibleCodes/issues

# Current Development Status

<br />Active Development: In Progress

# Updates

<br />11 / APRIL / 2023
<br />
<br />DEVELOPMENT UPDATE:
<br />TWITTER: @TorahBibleCodes https://twitter.com/TorahBibleCodes
<br />YOUTUBE: @TorahBibleCodes https://www.youtube.com/@TorahBibleCodes
<br />YOUTUBE: @TorahBibleCodes https://www.youtube.com/channel/UCNsvtMx4JJRpNzzPq57HCqg
<br /> BETA DEVELOPMENT PROGRAM (WORK-IN-PROGRESS) UPLOADED; More to come ASAP GOD-willing.
<br />
<br />Please support our efforts if you can by donating via GIVESENDGO: 
<br />https://www.givesendgo.com/torahbiblecodes
<br />
<br />OR via BITCOIN (BTC) to the following addresses:
<br />bc1qzws4zjgzf4wll2mtztsavmyvkg72fnajfff8r7

# Equidistant Letter Sequences (ELS)

<br />Witztum, Rips, and Rosenberg (WRR) define an Equidistant Letter Sequence (ELS) as a sequence of letters in the text whose positions - not counting spaces - form an arithmetic progression. That is to say the letters are found at the positions

n, n + d, n + 2d, ..., n + (k - 1)d

WRR define n as the start, d as the skip between letters in the search-term, and k as the length of the ELS. These three parameters uniquely identify the ELS which is denoted (n, d, k).

# The Texts Used:
## 1.) Genesis
https://github.com/TorahBibleCodes/Sefaria-Export/blob/master/json/Tanakh/Torah/Genesis/Hebrew/Tanach%20with%20Text%20Only.json

## 2.) Exodus
https://github.com/TorahBibleCodes/Sefaria-Export/blob/master/json/Tanakh/Torah/Exodus/Hebrew/Tanach%20with%20Text%20Only.json

## 3.) Leviticus
https://github.com/TorahBibleCodes/Sefaria-Export/blob/master/json/Tanakh/Torah/Leviticus/Hebrew/Tanach%20with%20Text%20Only.json

## 4.) Numbers
https://github.com/TorahBibleCodes/Sefaria-Export/blob/master/json/Tanakh/Torah/Numbers/Hebrew/Tanach%20with%20Text%20Only.json

## 5.) Deuteronomy
https://github.com/TorahBibleCodes/Sefaria-Export/blob/master/json/Tanakh/Torah/Deuteronomy/Hebrew/Tanach%20with%20Text%20Only.json

## 6.) Joshua

## 7.) Judges

## 8.) I Samuel

## 9.) II Samuel

## 10.) I Kings

## 11.) II Kings

## 12.) Isaiah

## 13.) Jeremiah

## 14.) Ezekiel

## 15.) Hosea

## 16.) Joel

## 17.) Amos

## 18.) Obadiah

## 19.) Jonah

## 20.) Micah

## 21.) Nahum

## 22.) Habakkuk

## 23.) Zephaniah

## 24.) Haggai

## 25.) Zechariah

## 26.) Malachi

## 27.) Psalms

## 28.) Proverbs

## 29.) Job

## 30.) Song of Songs

## 31.) Ruth

## 32.) Lamentations

## 33.) Ecclesiastes

## 34.) Esther

## 35.) Daniel

## 36.) Ezra

## 37.) Nehemiah

## 38.) I Chronicles

## 39.) II Chronicles


# How to Run the App / Program

READ THE DOCS: @TorahBibleCodes https://torahbiblecodes-sphinx.readthedocs.io/en/latest/index.html


# Structure of App / Program

<br />After running the Python file p.py, several Python / Pandas Objects are returned to you to interact with and further develop per your needs;
<br />We are currently developing the functionalities in the program to provide certain (many) specific data points, data objects, etc. so that scientifically repeatable (and therefore verifiable) results can be precisely measured, shared, tested, and either confirmed or disproved.
<br />The current BETA DEVELOPMENT version of the program does the following:

<ol>
	<li>Allows the user to select any text(s) from the Torah (Instruction) / Nevi'im (Prophets) / K'tuvim (Writings) of the Tanach (Hebrew Bible).</li>
	<li>Allows the user to choose a custom size of the 2D Matrix (X Rows by Y Columns) for the user-selected text(s) to be outputted to a CSV EXCEL file (CAUTION: Numbers approaching 1000 for X Rows will exceed the maximum allowed by EXCEL, and therefore will truncate the text).</li>
	<li>Allows the user to choose the number of desired ELS Search-Terms.</li>
	<li>Allows the user to input those specified ELS Search-Terms (NOTE: These must be typed in Hebrew characters, else EXCEPTION IS THROWN).</li>
	<li>Outputs CSV EXCEL file of the 2D Matrix for the selected text(s).</li>
	<li>Outputs CSV EXCEL file of the Gematria Number values for each word AND letter in the selected text(s)</li>
	<li>Outputs CSV EXCEL file of the Gematria Number values for each word AND letter in the ELS Search-Terms</li>
	<li>IN DEVELOPMENT:  Testing of several (best?) ways / algorithms for ELS Search within the text; Currently investigating REGEX, PANDAS, PURE PYTHON LINEAR SEARCH, etc.; Please see and examine the Python / Pandas Data Objects returned to see current capabilities in development.</li>
	<li>IN DEVELOPMENT:  Outputs CSV EXCEL file of the Data Points for each letter of each of the ELS Search-Terms so that precise, exact positions, shared positions, letter-proximity, statistical probability, etc. of letters will be scientifically verifiable and reproduceable.</li>
</ol>

<br />We invite you to share your open-source (alternative/multiple?) solutions of further development of this open-source program (e.g. add-ons, additional features, functionalities, GUIs, etc.), as well as scientific research using these software research tools with the community to allow confirmation of your discoveries and data, which will lead to further shared advancement and mutual benefit for us all


# Program Concepts:  Objects - D (DS), DL, D5, D5K, L (LLL), S (SSS), N (NW), W (DW), ListOfWords, NW4ELS, W4ELS (DW4ELS);

## "D" Object:  Dictionary of Verses Object

For any text chosen (e.g. Genesis, Exodus, Leviticus, Numbers, Deuteronomy, or all five (5) together, or all twenty-one (21) books of the Prophets, or all thirteen (13) books of the Writings, or all thirty-nine (39) books of the entire Hebrew Bible), the text is parsed and a Python dictionary D (and DS) is created that allows one to access each verse by 3-digit Tuple Key (Book, Chapter, Verse).  After choosing the text(s) to be searched, a Python dictionary D (and DS) is created to contain each verse - accessible by 3-digit Tuple Key.

## Each verse (and letter) of the thirty-nine (39) books of the Hebrew Bible is accessible via the Python dictionary "D" (or "DS") with a unique 3-digit Tuple Key as per following examples:

`<br />D[1,1,1] = GENESIS 1:1
<br />D[1,1,7] = GENESIS 1:7
<br />D[1,50,26] = GENESIS 50:26
<br />D[2,1,1] = EXODUS 1:1
<br />D[2,40,38] = EXODUS 40:38
<br />D[3,1,1] = LEVITICUS 1:1
<br />D[3,27,34] = LEVITICUS 27:34
<br />D[4,1,1] = NUMBERS 1:1
<br />D[4,36,13] = NUMBERS 36:13
<br />D[5,1,1] = DEUTERONOMY 1:1
<br />D[5,34,12] = DEUTERONOMY 34:12

<br />((1, 1, 1), 'בראשיתבראאלהיםאתהשמיםואתהארץ')
<br />((1, 1, 2), 'והארץהיתהתהוובהווחשךעלפניתהוםורוחאלהיםמרחפתעלפניהמים')
<br />((1, 1, 3), 'ויאמראלהיםיהיאורויהיאור')
<br />((1, 1, 4), 'ויראאלהיםאתהאורכיטובויבדלאלהיםביןהאורוביןהחשך')
<br />((1, 1, 5), 'ויקראאלהיםלאוריוםולחשךקראלילהויהיערבויהיבקריוםאחד')
<br />((1, 1, 6), 'ויאמראלהיםיהירקיעבתוךהמיםויהימבדילביןמיםלמים')
<br />((1, 1, 7), 'ויעשאלהיםאתהרקיעויבדלביןהמיםאשרמתחתלרקיעוביןהמיםאשרמעללרקיעויהיכן')
<br />((1, 1, 8), 'ויקראאלהיםלרקיעשמיםויהיערבויהיבקריוםשני')
<br />((1, 1, 9), 'ויאמראלהיםיקווהמיםמתחתהשמיםאלמקוםאחדותראההיבשהויהיכן')
<br />((1, 1, 10), 'ויקראאלהיםליבשהארץולמקוההמיםקראימיםויראאלהיםכיטוב')
<br />((1, 1, 11), 'ויאמראלהיםתדשאהארץדשאעשבמזריעזרעעץפריעשהפרילמינואשרזרעובועלהארץויהיכן')
<br />((1, 1, 12), 'ותוצאהארץדשאעשבמזריעזרעלמינהוועץעשהפריאשרזרעובולמינהוויראאלהיםכיטוב')
<br />((1, 1, 13), 'ויהיערבויהיבקריוםשלישי')
<br />((1, 1, 14), 'ויאמראלהיםיהימארתברקיעהשמיםלהבדילביןהיוםוביןהלילהוהיולאתתולמועדיםולימיםושנים')
<br />((1, 1, 15), 'והיולמאורתברקיעהשמיםלהאירעלהארץויהיכן')
<br />((1, 1, 16), 'ויעשאלהיםאתשניהמארתהגדליםאתהמאורהגדללממשלתהיוםואתהמאורהקטןלממשלתהלילהואתהכוכבים')
<br />((1, 1, 17), 'ויתןאתםאלהיםברקיעהשמיםלהאירעלהארץ')
<br />((1, 1, 18), 'ולמשלביוםובלילהולהבדילביןהאורוביןהחשךויראאלהיםכיטוב')
<br />((1, 1, 19), 'ויהיערבויהיבקריוםרביעי')
<br />((1, 1, 20), 'ויאמראלהיםישרצוהמיםשרץנפשחיהועוףיעופףעלהארץעלפנירקיעהשמים')
<br />((1, 1, 21), 'ויבראאלהיםאתהתנינםהגדליםואתכלנפשהחיההרמשתאשרשרצוהמיםלמינהםואתכלעוףכנףלמינהוויראאלהיםכיטוב')
<br />((1, 1, 22), 'ויברךאתםאלהיםלאמרפרוורבוומלאואתהמיםבימיםוהעוףירבבארץ')
<br />((1, 1, 23), 'ויהיערבויהיבקריוםחמישי')
<br />((1, 1, 24), 'ויאמראלהיםתוצאהארץנפשחיהלמינהבהמהורמשוחיתוארץלמינהויהיכן')
<br />((1, 1, 25), 'ויעשאלהיםאתחיתהארץלמינהואתהבהמהלמינהואתכלרמשהאדמהלמינהוויראאלהיםכיטוב')
<br />((1, 1, 26), 'ויאמראלהיםנעשהאדםבצלמנוכדמותנווירדובדגתהיםובעוףהשמיםובבהמהובכלהארץובכלהרמשהרמשעלהארץ')
<br />((1, 1, 27), 'ויבראאלהיםאתהאדםבצלמובצלםאלהיםבראאתוזכרונקבהבראאתם')
<br />((1, 1, 28), 'ויברךאתםאלהיםויאמרלהםאלהיםפרוורבוומלאואתהארץוכבשהורדובדגתהיםובעוףהשמיםובכלחיההרמשתעלהארץ')
<br />((1, 1, 29), 'ויאמראלהיםהנהנתתילכםאתכלעשבזרעזרעאשרעלפניכלהארץואתכלהעץאשרבופריעץזרעזרעלכםיהיהלאכלה')
<br />((1, 1, 30), 'ולכלחיתהארץולכלעוףהשמיםולכלרומשעלהארץאשרבונפשחיהאתכלירקעשבלאכלהויהיכן')
<br />((1, 1, 31), 'ויראאלהיםאתכלאשרעשהוהנהטובמאדויהיערבויהיבקריוםהששי')
<br />((1, 2, 1), 'ויכלוהשמיםוהארץוכלצבאם')
<br />((1, 2, 2), 'ויכלאלהיםביוםהשביעימלאכתואשרעשהוישבתביוםהשביעימכלמלאכתואשרעשה')
<br />((1, 2, 3), 'ויברךאלהיםאתיוםהשביעיויקדשאתוכיבושבתמכלמלאכתואשרבראאלהיםלעשות')
<br />((1, 2, 4), 'אלהתולדותהשמיםוהארץבהבראםביוםעשותיהוהאלהיםארץושמים')
<br />((1, 2, 5), 'וכלשיחהשדהטרםיהיהבארץוכלעשבהשדהטרםיצמחכילאהמטיריהוהאלהיםעלהארץואדםאיןלעבדאתהאדמה')
<br />((1, 2, 6), 'ואדיעלהמןהארץוהשקהאתכלפניהאדמה')
<br />((1, 2, 7), 'וייצריהוהאלהיםאתהאדםעפרמןהאדמהויפחבאפיונשמתחייםויהיהאדםלנפשחיה')
<br />((1, 2, 8), 'ויטעיהוהאלהיםגןבעדןמקדםוישםשםאתהאדםאשריצר')
<br />((1, 2, 9), 'ויצמחיהוהאלהיםמןהאדמהכלעץנחמדלמראהוטובלמאכלועץהחייםבתוךהגןועץהדעתטובורע')
<br />((1, 2, 10), 'ונהריצאמעדןלהשקותאתהגןומשםיפרדוהיהלארבעהראשים')
<br />((1, 2, 11), 'שםהאחדפישוןהואהסבבאתכלארץהחוילהאשרשםהזהב')
<br />((1, 2, 12), 'וזהבהארץההואטובשםהבדלחואבןהשהם')
<br />((1, 2, 13), 'ושםהנהרהשניגיחוןהואהסובבאתכלארץכוש')
<br />((1, 2, 14), 'ושםהנהרהשלישיחדקלהואההלךקדמתאשורוהנהרהרביעיהואפרת')
<br />((1, 2, 15), 'ויקחיהוהאלהיםאתהאדםוינחהובגןעדןלעבדהולשמרה')
<br />((1, 2, 16), 'ויצויהוהאלהיםעלהאדםלאמרמכלעץהגןאכלתאכל')
<br />((1, 2, 17), 'ומעץהדעתטובורעלאתאכלממנוכיביוםאכלךממנומותתמות')
<br />((1, 2, 18), 'ויאמריהוהאלהיםלאטובהיותהאדםלבדואעשהלועזרכנגדו')
<br />((1, 2, 19), 'ויצריהוהאלהיםמןהאדמהכלחיתהשדהואתכלעוףהשמיםויבאאלהאדםלראותמהיקראלווכלאשריקראלוהאדםנפשחיההואשמו')
<br />((1, 2, 20), 'ויקראהאדםשמותלכלהבהמהולעוףהשמיםולכלחיתהשדהולאדםלאמצאעזרכנגדו')
<br />((1, 2, 21), 'ויפליהוהאלהיםתרדמהעלהאדםויישןויקחאחתמצלעתיוויסגרבשרתחתנה')
<br />((1, 2, 22), 'ויבןיהוהאלהיםאתהצלעאשרלקחמןהאדםלאשהויבאהאלהאדם')
<br />((1, 2, 23), 'ויאמרהאדםזאתהפעםעצםמעצמיובשרמבשרילזאתיקראאשהכימאישלקחהזאת')
<br />((1, 2, 24), 'עלכןיעזבאישאתאביוואתאמוודבקבאשתווהיולבשראחד')
<br />((1, 2, 25), 'ויהיושניהםערומיםהאדםואשתוולאיתבששו')
<br />((1, 3, 1), 'והנחשהיהערוםמכלחיתהשדהאשרעשהיהוהאלהיםויאמראלהאשהאףכיאמראלהיםלאתאכלומכלעץהגן')
<br />((1, 3, 2), 'ותאמרהאשהאלהנחשמפריעץהגןנאכל')
<br />((1, 3, 3), 'ומפריהעץאשרבתוךהגןאמראלהיםלאתאכלוממנוולאתגעובופןתמתון')
<br />((1, 3, 4), 'ויאמרהנחשאלהאשהלאמותתמתון')
<br />((1, 3, 5), 'כיידעאלהיםכיביוםאכלכםממנוונפקחועיניכםוהייתםכאלהיםידעיטובורע')
<br />((1, 3, 6), 'ותראהאשהכיטובהעץלמאכלוכיתאוההואלעיניםונחמדהעץלהשכילותקחמפריוותאכלותתןגםלאישהעמהויאכל')
<br />((1, 3, 7), 'ותפקחנהעינישניהםוידעוכיעירמםהםויתפרועלהתאנהויעשולהםחגרת')
<br />((1, 3, 8), 'וישמעואתקוליהוהאלהיםמתהלךבגןלרוחהיוםויתחבאהאדםואשתומפנייהוהאלהיםבתוךעץהגן')
<br />((1, 3, 9), 'ויקראיהוהאלהיםאלהאדםויאמרלואיכה')
<br />((1, 3, 10), 'ויאמראתקלךשמעתיבגןואיראכיעירםאנכיואחבא')
<br />((1, 3, 11), 'ויאמרמיהגידלךכיעירםאתההמןהעץאשרצויתיךלבלתיאכלממנואכלת')
<br />((1, 3, 12), 'ויאמרהאדםהאשהאשרנתתהעמדיהואנתנהלימןהעץואכל')
<br />((1, 3, 13), 'ויאמריהוהאלהיםלאשהמהזאתעשיתותאמרהאשההנחשהשיאניואכל')
<br />((1, 3, 14), 'ויאמריהוהאלהיםאלהנחשכיעשיתזאתארוראתהמכלהבהמהומכלחיתהשדהעלגחנךתלךועפרתאכלכלימיחייך')
<br />((1, 3, 15), 'ואיבהאשיתבינךוביןהאשהוביןזרעךוביןזרעההואישופךראשואתהתשופנועקב')
<br />((1, 3, 16), 'אלהאשהאמרהרבהארבהעצבונךוהרנךבעצבתלדיבניםואלאישךתשוקתךוהואימשלבך')
<br />((1, 3, 17), 'ולאדםאמרכישמעתלקולאשתךותאכלמןהעץאשרצויתיךלאמרלאתאכלממנוארורההאדמהבעבורךבעצבוןתאכלנהכלימיחייך')
<br />((1, 3, 18), 'וקוץודרדרתצמיחלךואכלתאתעשבהשדה')
<br />((1, 3, 19), 'בזעתאפיךתאכללחםעדשובךאלהאדמהכיממנהלקחתכיעפראתהואלעפרתשוב')
<br />((1, 3, 20), 'ויקראהאדםשםאשתוחוהכיהואהיתהאםכלחי')
<br />((1, 3, 21), 'ויעשיהוהאלהיםלאדםולאשתוכתנותעורוילבשם')
<br />((1, 3, 22), 'ויאמריהוהאלהיםהןהאדםהיהכאחדממנולדעתטובורעועתהפןישלחידוולקחגםמעץהחייםואכלוחילעלם')
<br />((1, 3, 23), 'וישלחהויהוהאלהיםמגןעדןלעבדאתהאדמהאשרלקחמשם')
<br />((1, 3, 24), 'ויגרשאתהאדםוישכןמקדםלגןעדןאתהכרביםואתלהטהחרבהמתהפכתלשמראתדרךעץהחיים')
<br />((1, 4, 1), 'והאדםידעאתחוהאשתוותהרותלדאתקיןותאמרקניתיאישאתיהוה')
<br />((1, 4, 2), 'ותסףללדתאתאחיואתהבלויהיהבלרעהצאןוקיןהיהעבדאדמה')
<br />((1, 4, 3), 'ויהימקץימיםויבאקיןמפריהאדמהמנחהליהוה')
<br />((1, 4, 4), 'והבלהביאגםהואמבכרותצאנוומחלבהןוישעיהוהאלהבלואלמנחתו')
<br />((1, 4, 5), 'ואלקיןואלמנחתולאשעהויחרלקיןמאדויפלופניו')
<br />((1, 4, 6), 'ויאמריהוהאלקיןלמהחרהלךולמהנפלופניך')
<br />((1, 4, 7), 'הלואאםתיטיבשאתואםלאתיטיבלפתחחטאתרבץואליךתשוקתוואתהתמשלבו')
<br />`

## ... etc. ... etc. ... etc. ...

# Python Objects - D (DS), DL, D5, D5K, L (LLL), S (SSS), ListOfWords, N (NW), W (DW), ListOfSearchTerms, DictOfSearchTerms, NW4ELS, W4ELS (DW4ELS);

### Run the file "p.py" to see and interact with the following Python Objects:

### "D" Object: Python Dictionary of Verses (with No Spaces) with a 3-digit Tuple Key

### "DS" Object: Python Dictionary of Verses (with Spaces) with a 3-digit Tuple Key

### "DL" Object:  Python Dictionary of Letters with a 4-digit Tuple Key

### "D5" Object:  Python Dictionary of Letters with a 5-digit Tuple Key

### "D5K" Object:  Python Dictionary of 5-digit Tuple Key

### "L" Object:  Python List of Letters of the Selected Text(s)

### "LLL" Object:  Python List of Letters of the Selected Text(s) RECALCULATED FOR POSSIBLE BLANK SPACES IN LAST ROW OF 2D MATRIX

### "S" Object:  Python String of Letters of the Selected Text(s)

### "SSS" Object:  Python String of Letters of the Selected Text(s) RECALCULATED FOR POSSIBLE BLANK SPACES IN LAST ROW OF 2D MATRIX

### "ListOfWords" Object:  Python List of Words of the Selected Text(s)

### "N" Object:  Python List of Numbers for Letters of the Selected Text(s)

### "NW" Object:  Python List of Numbers for Words of the Selected Text(s)

### "W" Object:  Python List of Tuples of Words and Each Word's/Letter's Gematria Value

### "DW" Object:  Python Dict of Words and Each Word's/Letter's Gematria Value

### "ListOfSearchTerms" Object:  Python List of Words of the ELS Search-Terms

### "DictOfSearchTerms" Object:  Python Dictionary of Words of the ELS Search-Terms





## Each Verse can be further subdivided into a String (or List) Sequence of many Letter Objects (i.e. Strings of one (1) Letter only) which are classes which are accessible within the ELS Search sequence, and accessible by extension of previous tuple syntax:  Book, Chapter, Verse, Letter

### D Object - Dictionary of Verses (with No Spaces), accessible as data with a 3-digit Tuple Key
<br />D[1,1,1] --> GENESIS 1:1 - 1st Book, 1st Chapter, 1st Verse 
<br />D[1,1,2] --> GENESIS 1:2 - 1st Book, 1st Chapter, 2nd Verse
<br />D[1,1,3] --> GENESIS 1:3 - 1st Book, 1st Chapter, 3rd Verse

### DS Object - Dictionary of Verses (with Spaces), accessible as data with a 3-digit Tuple Key
<br />DS[1,1,1] --> GENESIS 1:1 - 1st Book, 1st Chapter, 1st Verse 
<br />DS[1,1,2] --> GENESIS 1:2 - 1st Book, 1st Chapter, 2nd Verse
<br />DS[1,1,3] --> GENESIS 1:3 - 1st Book, 1st Chapter, 3rd Verse

### D Object - Dictionary of Verses/Letters, accessible as data with a 3-digit Tuple Key + sub-element (0-indexed) in sequence of letters within each verse.
<br />D[1,1,1][0] --> 1st element (letter) in string/verse sequence --> 'ב'
<br />D[1,1,1][1] --> 2nd element (letter) in string/verse sequence --> 'ר'
<br />D[1,1,1][2] --> 3rd element (letter) in string/verse sequence --> 'א'
<br />D[1,1,1][-1] --> Last element in string/verse sequence...

### DL Object - Dictionary of Letters (with 4-digit key) with 4th element of tuple being the (non-0-indexed; 1-indexed) position of letter in verse...
<br />DL[1, 1, 1, 1] --> 'ב'
<br />DL[1, 1, 1, 2] --> 'ר'
<br />DL[1, 1, 1, 3] --> 'א'
<br />DL[1, 1, 1, 4] --> 'ש'
<br />DL[1, 1, 1, 5] --> 'י'
<br />DL[1, 1, 1, 6] --> 'ת'

<br />DL[5,34,12,43] --> 'י'
<br />DL[5,34,12,44] --> 'ש'
<br />DL[5,34,12,45] --> 'ר'
<br />DL[5,34,12,46] --> 'א'
<br />DL[5,34,12,47] --> 'ל'

### D5 Object - Dictionary of Letters (with 5-digit key) with 5th element of tuple being the position of letter in total sequence of text...(i.e. either all five (5) texts of the Torah together (304850 letters), or one (1) text only, or all twenty-one (21) texts of the Prophets, or all thirteen (13) texts of the Writings, or all thirty-nine (39) texts of the entire Hebrew Bible together)...
<br />D5[1, 1, 1, 1, 1] --> 'ב'
<br />D5[1, 1, 1, 2, 2] --> 'ר'
<br />D5[1, 1, 1, 3, 3] --> 'א'
<br />D5[1, 1, 1, 4, 4] --> 'ש'
<br />D5[1, 1, 1, 5, 5] --> 'י'
<br />D5[1, 1, 1, 6, 6] --> 'ת'

<br />D5[5, 34, 12, 43, 304846] --> 'י'
<br />D5[5, 34, 12, 44, 304847] --> 'ש'
<br />D5[5, 34, 12, 45, 304848] --> 'ר'
<br />D5[5, 34, 12, 46, 304849] --> 'א'
<br />D5[5, 34, 12, 47, 304850] --> 'ל'

### L Object - List of Letters
<br />L[0:6] --> ['ב', 'ר', 'א', 'ש', 'י', 'ת']
<br />L[-5:] --> ['י', 'ש', 'ר', 'א', 'ל']

### S Object - String of Letters
<br />S[0:6] --> 'בראשית'
<br />S[-5:] --> 'ישראל'


## N Object - List of Numbers:  Each letter's Kabbalah Numerical Gematria Value is obtainable by passing a string-sequence to a MODULE.FUNCTION() call (NOTE:  Numbers returned in the N Object are left-to-right; In previous, older versions of Python, Hebrew letters returned in L Object were R-T-L right-to-left; However, in current our development version of Python 3.9, these same Hebrew letters returned are L-T-R left-to-right, so now the Hebrew letter order is exactly the same as all other orders in the Python Lists: L-T-R).
<br />ListOfLetters =  ['ב', 'ר', 'א', 'ש', 'י', 'ת']

<br />N = mod_9GetNumberValue.fn_GetNumberValue(ListOfLetters) --> [2, 200, 1, 300, 10, 400]

### א = 1
### ב = 2
### 3 = ג
### 4 = ד
### 5 = ה
### 6 = ו
### 7 = ז
### 8 = ח
### 9 = ט
### 10 = י
### 20 = כ / ך
### 30 = ל
### 40 = מ / ם
### 50 = נ / ן
### 60 = ס
### 70 = ע
### 80 = פ / ף
### 90 = צ / ץ
### 100 = ק
### 200 = ר
### 300 = ש
### 400 = ת

# Pandas Objects: sL0 (sL) / sLLL0 (sLLL)

<br />## PD SERIES OF THE SELECTED TEXT(S); ## LETTER POSITIONS ARE DYNAMICALLY GENERATED DEPENDING UPON SPECIFIC TEXT(S) SELECTED; e.g. the 5th book selected may (or may not) be Deuteronomy as the 5th Book of Torah, or the 5th Book of the Prophets, or the 5th Book of the Writings.
<br />

<br />## CREATE PD SERIES WITH 0-INDEX FOR THE ORIGINAL TEXT LENGTH
<br />sL0 = pd.Series(L) ## --> Converts ListOfLetters to Pandas Series (~ Dictionary-like Object)
<br />    
<br />## CREATE PD SERIES WITH 1-INDEX FOR THE ORIGINAL TEXT LENGTH
<br />sL = pd.Series(L, index=ListOfIndexesCustomL) ## --> Converts ListOfLetters to Pandas Series (~ Dictionary-like Object) with custom indexes for keys of the PD Series starting with 1-index/key
<br />
<br />## CREATE PD SERIES WITH 0-INDEX FOR LENGTH OF THE TEXT + EMPTY SPACES IN LAST ROW 
<br />sLLL0 = pd.Series(LLL) ## --> Converts ListOfLetters to Pandas Series (~ Dictionary-like Object)
<br />    
<br />## CREATE PD SERIES WITH 1-INDEX FOR LENGTH OF THE TEXT + EMPTY SPACES IN LAST ROW
<br />sLLL = pd.Series(LLL, index=ListOfIndexesCustomLLL) ## --> Converts ListOfLetters to Pandas Series (~ Dictionary-like Object) with custom indexes for keys of the PD Series starting with 1-index/key


# CENTRAL ELS SEARCH ALGORITHM:
<br />n, (n + d), (n + 2d), (n + 3d)... (n + (k-1)d)
<br />
<br />sL[6] ## == 'ת' == (n) ## WHEN TEXT SELECTED == 1 GENESIS
<br />sL[6+50] ## == 'ו' == (n + d)
<br />sL[6+50+50] ## == 'ר' == (n + 2d)
<br />sL[6+50+50+50] ## = 'ה' == (n + 3d) ## k == 4 == LengthOfELSSearchTerm
<br />
<br />sL[6] ## == 'ת' == (n) ## WHEN TEXT SELECTED == 1 GENESIS
<br />sL[56] ## == 'ו' == (n + d)
<br />sL[106] ## == 'ר' == (n + 2d)
<br />sL[156] ## = 'ה' == (n + 3d)


# Useful CLI Commands
sL.str.startswith("ב")
--> Returns Boolean (True/False) for each match (True) and for each non-match (False)

sL.str.endswith("ב")
--> Returns Boolean (True/False) for each match (True) and for each non-match (False)

sL.str.find("ב")
--> Returns Boolean-like (0 / -1) for each match (0) and for each non-match (-1)

sL.str.rfind("ב")
--> Returns Boolean-like (0 / -1) for each match (0) and for each non-match (-1)

### The following values are all equivalent; Each equals every other value
<ul>
  <li>len(sL) --> Total Number of Letters in the Pandas Series s --> Equal to len(S); len(L); len(DL); len(D5); len(N)</li>
  <li>len(S) --> Total Number of Letters in the Python String S --> Equal to len(sL); len(L); len(DL); len(D5); len(N)</li>
  <li>len(L) --> Total Number of Letters in the Python List L --> Equal to len(sL); len(S); len(DL); len(D5); len(N)</li>
  <li>len(DL) --> Total Number of Letters in the Python Dictionary DL with 4-digit Tuple Key --> Equal to len(sL); len(S); len(L); len(D5); len(N)</li>
  <li>len(D5) --> Total Number of Letters in the Python Dictionary D5 with 5-digit Tuple Key --> Equal to len(sL); len(S); len(L); len(DL); len(N)</li>
  <li>len(N) --> Total Number of Numbers in the Python List N --> Equal to len(sL); len(S); len(L); len(DL); len(D5)</li>
  
</ul>

# Statistics
### Total Number of Verses in Torah: 5846
### Total Number of Letters in Torah:  304850
Total Number of Letter א Aleph in Torah: 27060
<br />Total Number of Letter ב Bet in Torah: 16345
<br />Total Number of Letter ג Gimel in Torah: 2109
<br />Total Number of Letter ד Daled in Torah: 7032
<br />Total Number of Letter ה Heh/Hey/Hay in Torah: 28055
<br />Total Number of Letter ו Vav in Torah: 30533
<br />Total Number of Letter ז Zayin in Torah: 2198
<br />Total Number of Letter ח Ḥet in Torah: 7189
<br />Total Number of Letter ט Tet in Torah: 1804
<br />Total Number of Letter י Yud in Torah: 31556
<br />Total Number of Letter כ Khaf in Torah: 8610
<br />Total Number of Letter ך Khaf Sofit in Torah: 3358
<br />Total Number of Letter ל Lamed in Torah: 21570
<br />Total Number of Letter מ Mem in Torah: 14466
<br />Total Number of Letter ם Mem Sofit in Torah: 10624
<br />Total Number of Letter נ Nun in Torah: 9867
<br />Total Number of Letter ן Nun Sofit in Torah: 4259
<br />Total Number of Letter ס Samekh in Torah: 1833
<br />Total Number of Letter ע 'Ain in Torah: 11250
<br />Total Number of Letter פ Peh/Pey/Pay in Torah: 3975
<br />Total Number of Letter ף Peh/Pey/Pay Sofit in Torah: 830
<br />Total Number of Letter צ Tzadik in Torah: 2927
<br />Total Number of Letter ץ Tzadik Sofit in Torah: 1035
<br />Total Number of Letter ק Kuf in Torah: 4695
<br />Total Number of Letter ר Resh in Torah: 18125
<br />Total Number of Letter ש Shin in Torah: 15595
<br />Total Number of Letter ת Taf in Torah: 17950

### Total Number of Verses in Genesis:  1533
### Total Number of Letters in Genesis:  78069

Total Number of Letter א in Book of Genesis: 7634
<br />Total Number of Letter ב in Book of Genesis: 4332
<br />Total Number of Letter ג in Book of Genesis: 577
<br />Total Number of Letter ד in Book of Genesis: 1848
<br />Total Number of Letter ה in Book of Genesis: 6283
<br />Total Number of Letter ו in Book of Genesis: 8447
<br />Total Number of Letter ז in Book of Genesis: 428
<br />Total Number of Letter ח in Book of Genesis: 1844
<br />Total Number of Letter ט in Book of Genesis: 308
<br />Total Number of Letter י in Book of Genesis: 9041
<br />Total Number of Letter כ in Book of Genesis: 1909
<br />Total Number of Letter ך in Book of Genesis: 865
<br />Total Number of Letter ל in Book of Genesis: 5275
<br />Total Number of Letter מ in Book of Genesis: 3421
<br />Total Number of Letter ם in Book of Genesis: 2689
<br />Total Number of Letter נ in Book of Genesis: 2776
<br />Total Number of Letter ן in Book of Genesis: 1009
<br />Total Number of Letter ס in Book of Genesis: 446
<br />Total Number of Letter ע in Book of Genesis: 2823
<br />Total Number of Letter פ in Book of Genesis: 890
<br />Total Number of Letter ף in Book of Genesis: 313
<br />Total Number of Letter צ in Book of Genesis: 740
<br />Total Number of Letter ץ in Book of Genesis: 351
<br />Total Number of Letter ק in Book of Genesis: 1301
<br />Total Number of Letter ר in Book of Genesis: 4793
<br />Total Number of Letter ש in Book of Genesis: 3574
<br />Total Number of Letter ת in Book of Genesis: 4152

### Total Number of Verses in Hebrew Bible: 23206
### Total Number of Letters in Hebrew Bible: 1197042

Total Number of Letter א in Hebrew Bible: 95685
<br />Total Number of Letter ב in Hebrew Bible: 65216
<br />Total Number of Letter ג in Hebrew Bible: 10080
<br />Total Number of Letter ד in Hebrew Bible: 32371
<br />Total Number of Letter ה in Hebrew Bible: 101962
<br />Total Number of Letter ו in Hebrew Bible: 129606
<br />Total Number of Letter ז in Hebrew Bible: 9099
<br />Total Number of Letter ח in Hebrew Bible: 27598
<br />Total Number of Letter ט in Hebrew Bible: 6310
<br />Total Number of Letter י in Hebrew Bible: 137870
<br />Total Number of Letter כ in Hebrew Bible: 33466
<br />Total Number of Letter ך in Hebrew Bible: 14002
<br />Total Number of Letter ל in Hebrew Bible: 88302
<br />Total Number of Letter מ in Hebrew Bible: 57638
<br />Total Number of Letter ם in Hebrew Bible: 41291
<br />Total Number of Letter נ in Hebrew Bible: 39852
<br />Total Number of Letter ן in Hebrew Bible: 15241
<br />Total Number of Letter ס in Hebrew Bible: 7635
<br />Total Number of Letter ע in Hebrew Bible: 44811
<br />Total Number of Letter פ in Hebrew Bible: 15730
<br />Total Number of Letter ף in Hebrew Bible: 2554
<br />Total Number of Letter צ in Hebrew Bible: 11689
<br />Total Number of Letter ץ in Hebrew Bible: 3288
<br />Total Number of Letter ק in Hebrew Bible: 16278
<br />Total Number of Letter ר in Hebrew Bible: 68064
<br />Total Number of Letter ש in Hebrew Bible: 58198
<br />Total Number of Letter ת in Hebrew Bible: 63206

