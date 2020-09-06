
.. activecode:: TransformingSequences_week4a1_asign_c01_03
    :prim_comp: ITER05, ITER06, COND02
    :supp_comp: VES03, OP04, OP09, DT02, SEQ02, STR01, STR05, STR06, ITER01
    :language: python
    
    Write code that uses the string stored in ``sent`` and creates an acronym which is assigned 
    to the variable ``acro``. The first two letters of each word should be used, each letter in 
    the acronym should be a capital letter, and each element of the acronym should be separated by 
    a ". " (dot and space). Words that should not be included in the acronym are stored in the list 
    ``stopwords``. For example, if ``sent`` was assigned the string "height and ewok wonder" then 
    the resulting acronym should be "HE. EW. WO".
    ~~~~
    stopwords = ['to', 'a', 'for', 'by', 'an', 'am', 'the', 'so', 'it', 'and', 'The']
    sent = "The water earth and air are vital"

    ====