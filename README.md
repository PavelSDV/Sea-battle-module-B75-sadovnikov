# skillfactory-module-B75-sadovnikov

-------------------
Задание.

напишите следующее приложение:

Суть написанного приложения — игра «Морской бой».

Интерфейс приложения должен представлять из себя консольное окно с двумя полями 6х6 вида:

    | 1 | 2 | 3 | 4 | 5 | 6|

1 | О | О | О | О | О | О |

2 | О | О | О | О | О | О |

3 | О | О | О | О | О | О |

4 | О | О | О | О | О | О |

5 | О | О | О | О | О | О |

6 | О | О | О | О | О | О |

Игрок играет с компьютером. Компьютер делает ходы наугад, но не ходит по тем клеткам, в которые он уже сходил.
Для представления корабля опишите класс Ship с конструктором принимающим в себя набор точек (координат) на игровой доске.
Опишите класс доски. Доска должна принимать в конструкторе набор кораблей.
Корабли должны находится на расстоянии минимум одна клетка друг от друга.
Корабли на доске должны отображаться следующим образом (пример):

   | 1 | 2 | 3 | 4 | 5 | 6|

1 | ■ | ■ | ■ | О | О | О |

2 | О | О | О | О | ■ | ■ |

3 | О | О | О | О | О | О |

4 | ■ | О | ■ | О | ■ | О |

5 | О | О | О | О | ■ | О |

6 | ■ | О | ■ | О | О | О |

На каждой доске (у ИИ и у игрока) должно находится следующее количество кораблей: 1 корабль на 3 клетки, 2 корабля на 2 клетки, 4 корабля на одну клетку.
Запретите игроку стрелять в одну и ту же клетку несколько раз. При ошибках хода игрока должно возникать исключение.

   | 1 | 2 | 3 | 4 | 5 | 6|

1 | X | X | X | О | О | О |

2 | О | О | О | X | X | О |

3 | О | T | О | О | О | О |

4 | ■ | О | ■ | О | ■ | О |

5 | О | О | О | О | ■ | О |

6 | ■ | О | ■ | О | О | О |

В случае, если возникают непредвиденные ситуации, выбрасывать и обрабатывать исключения.
Буквой X помечаются подбитые корабли, буквой T — промахи.

Побеждает тот, кто быстрее всех разгромит корабли противника.

--------------------
Итоговая оценка

31
из 31
баллов

1
Ячейки игрока и компьютера отображаются корректно
Отлично
5 балла

2
Компьютер делает правильные ходы и не ходит в одни и те же клетки
Отлично
5 балла
3
Игрок не может ходить в одно и то же место на игровом поле по несколько раз
Отлично
3 балла

4
Игра заканчивается при разгроме всех кораблей одной из сторон
Отлично
5 балла

5
Использован объектно-ориентированный подход
Со всеми принципами ООП
5 балла

6
Есть отлов собственно выбрасываемых исключений в функциях или методах
Отлично
2 балла

7
Точки для хранения координат
Представляют из себя собственный тип данных
1 балла

8
Описаны классы корабля и игрового поля
Отлично
5 балла

Здравствуйте!
Работа оценена максимальными баллами по каждому критерию.
Благодарю за качественно проделанную работу, вы выполнили все критерии, создали нужные классы.
В игре учтены ход компьютера, занятая клетка, интерфейс интуитивно понятен.
В целом отличная работа!
Проверку выполнила ментор Попова Екатерина.
Если у вас остались вопросы, вы можете обратиться в канал #module_b7 в Slack
