.. parsonsprob:: TransformingSequences_week4a1_assess_question5_2_1_2
    :prim_comp: DT03, ITER05, COND02
    :supp_comp: OP04, SEQ02, ITER01, NEST01
    :numbered: left
    :adaptive:
    
    Arrange the following lines of code so that you can accumulate the total number of strings in the list.
    
    The code blocks contain ``two extra blocks`` that is not needed in a correct solution.</p>
    -----
    lst = ['plan', 'answer', 5, 9.29, 'order, items', [4]]
    s = 0
    =====
    for item in lst:
    =====
    for n in lst: #distractor
    =====
        if type(item) == type("string"):
    =====
            s = s + 1
    =====
            s = s + n #distractor