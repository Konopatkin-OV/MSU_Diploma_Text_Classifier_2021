# 

Классификатор, различающий искусственные тексты, сгенерированные сетью ruGPT-3. (<i>https://sbercloud.ru/ru/warp/gpt-3</i>) <br>
Признаки текста выделяются при помощи метода GLTR. (<i>http://gltr.io/</i>) <br>
К полученным признакам применяется классификатор на основе ансамбля деревьев решений, полученный методом адаптивного бустинга. (<i>https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html</i>) <br>
