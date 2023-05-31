# projeto1_OrientacaoObjetos
Projeto simples com a criação de conta em banco:
1 - Criação da classe: class Conta
2 - Criação do contrutor: __init__ com os atributos da conta:
  2.1 - numero
  2.2 - titular
  2.3 - saldo
  2.4 - limite

#  projeto1_OrientacaoObjetos aprimoramento do codigo com encapsulamento de atributos
Código melhorado com encapsulamento dos atributos
OBS: Em python o encapsulamento é entendido com dois underscores colocados a frente do nome dos atributos, exemplo__atributo.

#  projeto1_OrientacaoObjetos aprimoramento do codigo com criação de métodos(do objeto), métodos privados(do objeto), métodos estaticos(da classe)
Código melhorado com criação dos seguintes métodos:
1 - Métodos: estrato, deposita, sacar, transferencia
2 - Métodos privados: todos os métodos que contem underscore, exemplo: metodo__pode_sacar
3 - Métodos estaticos:  todos os métodos com @statisticmethod, exemplo: cod_banco
4 - Métodos get:  todos os metodos com @property, exemplos: saldo, titular e limite
  OBS: Método get vai acessar o valor do atributo pelo metodo somente para mostrar seu valor
5 - Métodos set: todos os métodos com @noome_metodo.setter, exemplo: limite
  OBS: Método set vai acessar o atributo pelo metodo para alterar seu valor
