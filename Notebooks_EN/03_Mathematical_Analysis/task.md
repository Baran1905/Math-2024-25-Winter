# Çözümler

## 1. \( y'(x) = y \)
Bu bir **ayrılabilir diferansiyel denklem**dir. Adım adım çözelim:

### Adım 1: Denklemi yeniden yazalım
$$ \frac{dy}{dx} = y $$
Değişkenleri ayırıyoruz:
$$ \frac{1}{y} \, dy = dx $$

### Adım 2: Her iki tarafı da integral alalım
$$ \int \frac{1}{y} \, dy = \int 1 \, dx $$
$$ \ln|y| = x + C $$
Burada $C$ entegrasyon sabitidir.

### Adım 3: \( y \) için çözüm yapalım
Logaritmayı kaldırmak için her iki tarafın üstelini alalım:
$$ |y| = e^{x+C} $$
$$ y = Ce^x $$
Burada $C = e^C$ sabiti kapsıyor.

**Sonuç**:
$$ y(x) = Ce^x $$

---

## 2. \( y'(x) = \frac{1}{2y(x)} \)
Bu da **ayrılabilir bir diferansiyel denklem**dir. Adım adım çözelim:

### Adım 1: Denklemi yeniden yazalım
$$ \frac{dy}{dx} = \frac{1}{2y} $$
Değişkenleri ayırıyoruz:
$$ 2y \, dy = dx $$

### Adım 2: Her iki tarafı da integral alalım
$$ \int 2y \, dy = \int 1 \, dx $$
$$ y^2 = x + C $$
Burada $C$ entegrasyon sabitidir.

### Adım 3: \( y \) için çözüm yapalım
Her iki tarafın karekökünü alalım:
$$ y = \pm \sqrt{x + C} $$

**Sonuç**:
$$ y(x) = \pm \sqrt{x + C} $$

---

## Çözüm Özetleri

1. \( y'(x) = y \) denklemi için:
   $$ y(x) = Ce^x $$

2. \( y'(x) = \frac{1}{2y(x)} \) denklemi için:
   $$ y(x) = \pm \sqrt{x + C} $$