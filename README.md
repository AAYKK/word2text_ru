# word2text_ru
Перевод чисел в текст на python

Следующие функции умеют выводить число прописью на русском языке, а так же считать НДС и переводить сумму в вид для договораЖ
Сейчас всё станет понятнее:

Переведём число 123 в вид "сто двадцать три":
        from word2text_ru import Word2text as w2t
        print(w2t(123)
        >>>"сто двадцать три"


Так же выведем допустимый вид текста для договра из числа 123.15 договора:
        from word2text_ru import summa
        print(summa(123.15)
        >>>123 (сто двадцать три) рубля 15 копеек


Выведем НДС(20%) для суммы 123 руб:
        from word2text_ru import nds
        print(nds(123))
        >>>20.5 рублей
