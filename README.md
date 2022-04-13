# Хакатон BestHack'22 в секции DataScience

# Задание
Учитывая все сложности необходимо разработать модель машинного обучения, способную идентифицировать человека из заданной выборки по переданной в нее электрокардиограммах

# Сложности, с которыми придется столкнуться
•	Сигнал имеет много помех, его необходимо сгладить
•	Визуально кардиограмма может быть у двух человек похожа
•	ЭКГ может содержать различного рода заболевания (аритмии, фибрилляции), что усложняет распознавание ритма. Частота Сердечных Сокращений (ЧСС) может увеличиваться и уменьшаться на записи, поэтому необходимо четко выделять удары сердца
•	Возможна дыхательная аритмия (т.е. задержка ритма, связанная с изменением дыхания)

# Критерии оценки
Качество модели будет оцениваться по метрике F1-взвешенное

# Дополнительные баллы
Дополнительные баллы можно получить, если система будет способна отличить здорового человека от больного (больным считается тот, у кого имеются отклонения в сердечном ритме) или способна по ЭКГ приблизительно дать информацию о человеке (пол, возраст)
