User -> UI : press '7'
User -> UI : press '+'
User -> UI : press '3'
User -> UI : press '*'
User -> UI : press '4'
User -> UI : press '='
UI -> Parser/Evaluator : send expression "7+3*4"
Evaluator -> Evaluator : parse, compute with precedence => 19
Evaluator -> UI : return result 19
UI -> User : display 19