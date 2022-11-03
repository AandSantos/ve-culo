# ve-culo

class transporte():
    def __init__(self,modelo,km):
        self.modelo = modelo
        self.km = km

    def get_modelo(self):
        return self.modelo

    def set_modelo(self,novo_modelo):
        self.modelo = novo_modelo

    def get_km(self):
        return self.km

    def set_km(self,novo_km):
        self.km = novo_km

veic_1 = transporte((input('Que tipo de carro você usava? ')),int(input('Enquanto estava a sua quilometragem? ')))
veic_1.get_modelo()
veic_1.get_km()
veic_1.set_modelo(input('Qual o seu veículo agora? '))
veic_1.get_modelo()
veic_1.get_km()
veic_1.set_km(int(input('Qual a quilometragem do seu novo veículo? ')))
veic_1.get_modelo()
veic_1.get_km()
print('='*60)
print('O novo veículo do condutor é um(a) {} com {}Km rodados.'.format(veic_1.get_modelo(),veic_1.get_km()))
print('='*60)
veic_2 = transporte((input('Que tipo de carro você usava? ')),int(input('Enquanto estava a sua quilometragem? ')))
veic_2.get_modelo()
veic_2.get_km()
veic_2.set_modelo(input('Qual é o seu veículo agora? '))
veic_2.get_modelo()
veic_2.get_km()
veic_2.set_km(int(input('Qual é a quilometragem do seu novo veículo? ')))
veic_2.get_modelo()
veic_2.get_km()
print('='*60)
print('O novo veículo do condutor é um(a) {} com {}Km rodados.'.format(veic_2.get_modelo(),veic_2.get_km()))
print('='*60)
