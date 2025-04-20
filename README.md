# 🌱 FarmTech Solutions - Modelagem de Banco de Dados  

## **📝 MER (Modelo Entidade-Relacionamento)**  
### **Entidades Principais**  
| Entidade       | Descrição                                  | Atributos (Exemplo)                     |  
|----------------|-------------------------------------------|-----------------------------------------|  
| `Cultura`      | Dados das plantações (ex: soja, milho).   | `id_cultura (PK)`, `nome`, `area`       |  
| `Sensor`       | Sensores de umidade, pH, NPK.             | `id_sensor (PK)`, `tipo`, `localizacao` |  
| `Leitura`      | Registros de medições.                    | `id_leitura (PK)`, `valor`, `data_hora` |  

### **Relacionamentos**  
- **1 Cultura** → **N Leituras** (1:N)  
- **1 Sensor** → **N Leituras** (1:N)  

## **📊 DER (Diagrama Entidade-Relacionamento)**  
![Diagrama DER](docs/der.png)  

## **⚙️ Como Visualizar o Modelo**  
1. Baixe o arquivo `docs/modelo.dmd`.  
2. Abra no **Oracle SQL Developer Data Modeler**.  

## **👥 Autores**  
- [Nicolas Paulino Ávila] - RM564312  
