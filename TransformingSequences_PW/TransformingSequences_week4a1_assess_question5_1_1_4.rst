
.. mchoice:: TransformingSequences_week4a1_assess_question5_1_1_4
    :prim_comp: ITER05
    :supp_comp: VES03, OP04, STR01, STR04, ITER01
   :answer_a: phrase
   :answer_b: rest
   :answer_c: let
   :correct: a
   :feedback_a: Good work!
   :feedback_b: rest is the sequence, not the iterator variable.
   :feedback_c: let is the accumulator variable, not the iterator variable.
   :practice: T
   :topics: TransformingSequences/TheAccumulatorPatternwithLists

   Which of these is the iterator (loop) variable?

   .. sourcecode:: python

    rest = ["sleep", 'dormir', 'dormire', "slaap", 'sen', 'yuxu', 'yanam']
    let = ''
    for phrase in rest:
        let += phrase[0]