.. mchoice:: TransformingSequences_week4a1_assess_question5_1_1_1
    :prim_comp: ITER05
    :supp_comp: VES03, OP04, STR01, ITER01
   :answer_a: byzo
   :answer_b: x
   :answer_c: z
   :answer_d: c
   :correct: d
   :feedback_a: This is the variable with our string, but it does not accumulate anything.
   :feedback_b: This is the iterator variable. It changes each time but does not accumulate.
   :feedback_c: This is a variable inside the for loop. It changes each time but does not accumulate or retain the old expressions that were assigned to it.
   :feedback_d: Yes, this is the accumulator variable. By the end of the program, it will have a full count of how many items are in byzo.
   :practice: T
   :topics: TransformingSequences/TheAccumulatorPatternwithStrings

   Which of these is the accumulator variable?

   .. sourcecode:: python

    byzo = 'hello world!'
    c = 0
    for x in byzo:
        z = x + "!"
        print(z)
        c = c + 1