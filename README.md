# -1-feature-lab1--Pashkevich-feature-lab1-Roman.
SELECT R3.ПІП_студента, R4.Дисципліна
FROM R1
JOIN R3 ON R1.код_студента = R3.код_студента
JOIN R4 ON R1.код_дисципліни = R4.код_дисципліни
WHERE R1.Оцінка = 'Відмінно';
