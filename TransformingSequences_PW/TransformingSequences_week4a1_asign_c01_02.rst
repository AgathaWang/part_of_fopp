
.. activecode:: TransformingSequences_week4a1_asign_c01_02
    :prim_comp: ITER05, ITER06, COND02
    :supp_comp: VES03, OP04, OP09, DT02, SEQ02, STR01, STR04, STR06, ITER01
    :language: python
    
    Write code that uses the string stored in ``org`` and creates an acronym which is assigned 
    to the variable ``acro``. Only the first letter of each word should be used, each letter 
    in the acronym should be a capital letter, and there should be nothing to separate the letters 
    of the acronym. Words that should not be included in the acronym are stored in the list ``stopwords``. 
    For example, if ``org`` was assigned the string "hello to world" then the resulting acronym should be "HW".
    ~~~~
    stopwords = ['to', 'a', 'for', 'by', 'an', 'am', 'the', 'so', 'it', 'and', "The"]
    org = "The organization for health, safety, and education"

    ====