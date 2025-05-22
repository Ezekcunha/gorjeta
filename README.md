# gorjeta
def calcular_gorjeta(valor_conta: float, porcentagem_gorjeta: float) -> float:
  """
  Calcula o valor da gorjeta a ser deixada em um restaurante.

  Args:
    valor_conta (float): O valor total da conta.
    porcentagem_gorjeta (float): A porcentagem da gorjeta (ex: 15 para 15%).

  Returns:
    float: O valor da gorjeta calculado.
  """
  gorjeta = valor_conta * (porcentagem_gorjeta / 100)
  return gorjeta

# Exemplo de uso:
valor_total_da_conta = 100.00
porcentagem_desejada = 15

gorjeta_calculada = calcular_gorjeta(valor_total_da_conta, porcentagem_desejada)
print(f"O valor da gorjeta a ser deixada é: R${gorjeta_calculada:.2f}")

valor_total_da_conta_2 = 75.50
porcentagem_desejada_2 = 10

gorjeta_calculada_2 = calcular_gorjeta(valor_total_da_conta_2, porcentagem_desejada_2)
print(f"O valor da gorjeta a ser deixada é: R${gorjeta_calculada_2:.2f}")
