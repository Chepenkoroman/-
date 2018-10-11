#JSGF V1.0;

grammar ;

<greet> = (здравствуйте|здравствуй|привет|приветствую);
<represent> = (меня зовут|моё имя|мое имя);
<status> = (On|Off);
<link.normal> = (2G|3G|LTE|EDGE);
<link.simple> = (два джи|три джи);
<links> = <link.normal>|<link.simple>;
public <query> = <greet> <expression>;
