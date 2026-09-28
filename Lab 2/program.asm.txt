STRING Enter_a_number:_
STRING The_double_is:_
STRING ~


DATA n 0


LABEL start
OUTSN 0
READN R1 0
JZER R1 end
MULN R1 2
STORE R1 n


OUTSN 1
LOADM R1 n
OUTR R1 0
OUTSN 2


JUMP start


LABEL end
STOP