# trading
# -------------------
# Ejemplo de uso
# -------------------
bond = Bond(face_value=1000, coupon_rate=0.05, periods=5, yield_rate=0.04)

print("Flujos:", bond.cash_flows())      # [50, 50, 50, 50, 1050]
print("Precio del bono:", round(bond.price(), 2))
print("Duración de Macaulay:", round(bond.macaulay_duration(), 4))
