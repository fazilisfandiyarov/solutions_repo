# Xülasə
Deterministik xaos nəzəriyyəsi, deterministik dinamik sistemlərdə görünən qeyri-müntəzəm və gözəgörünməz davranışları öyrənir.

# Əsas Anlayışlar
## Deterministik Xaosun Xüsusiyyətləri
Deterministiklik: Sistemin gələcək vəziyyəti cari vəziyyət və dinamika qanunları ilə tam müəyyən edilir

Həssaslıq ilkin şərtlərə: Kiçik başlanğıc fərqləri zamanla sürətlə böyüyür

Qeyri-xətti dinamika: Sadə təkrarlanan proseslər mürəkkəb davranışlar yarada bilər

# Riyazi Modellər
## Loqistik Xəritə
$f(x) = rx(1-x)$

burada:

$x$: sistemin vəziyyəti

$r$: parametr

## Lorenz Attraktoru
$\frac{dx}{dt} = \sigma(y - x)$

$\frac{dy}{dt} = x(\rho - z) - y$

$\frac{dz}{dt} = xy - \beta z$

# Xaos Nümunələri
| Sistem Növü | Nümunə |
|-------------|--------|
| Hava | Atmosfer dinamikası |
| Fiziki | Maye axını, turbulent axın |
| Bioloji | Əhali dinamikası |
| İqtisadi | Bazar dalğalanmaları |

# Kod Nümunələri
## Python ilə Loqistik Xəritə
```python
def logistic_map(r, x):
    return r * x * (1 - x)