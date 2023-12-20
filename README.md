## Genetik Algoritma ile Knapsack Problemi Çözümü
Bu proje, genetik algoritma kullanarak bir çanta problemi olan "Knapsack Problemi"ni çözmek için basit bir Python uygulamasını içermektedir.

> Knapsack Problemi Nedir?

Knapsack Problemi, bir çantanın belirli bir kapasitesi olduğu ve çanta içine konulacak nesnelerin ağırlıkları ve önem düzeyleri verildiğinde, çantaya konulacak nesnelerin seçilmesiyle ilgilenen bir kombinasyon optimizasyon problemidir. Bu problem, genetik algoritmalar gibi metaheuristik yöntemlerle çözülebilir.
## Parametreler
Proje dosyasındaki genetik algoritma için bazı temel parametreler şu şekildedir:

- tools: Çözümde kullanılacak nesnelerin listesi. Her bir nesnenin önem düzeyi ve ağırlığı belirlenmiştir.
- capacity: Çantanın maksimum kapasitesi.
- population_size: Popülasyon büyüklüğü.
- generations: Jenerasyon sayısı.
- crossover_probability: Çaprazlama olasılığı.
- mutation_probability: Mutasyon olasılığı.

Bu parametreleri kendi ihtiyaçlarınıza göre özelleştirebilirsiniz.

## Sonuçlar
Genetic Algorithm Results:
| Generation Count | Best Individual       | Iteration Found | Total Function Calls | Average Function Calls | Standard Deviation |
|-------------------|-----------------------|------------------|-----------------------|------------------------|---------------------|
| 100               | [1, 1, 0, 1, 1, 0, 0] | 13               | 3330                   |33.30                   | 1.4                 |

## 🛠️ Kurulum

1.Terminal veya Komut İstemcisini açın.

2.Klonlamak istediğiniz dizine gitmek için cd komutunu kullanın. Örneğin, masaüstüne klonlamak istiyorsanız
```bash
cd Desktop
```
3.Proje sayfasındaki yeşil "Code" düğmesine tıklayın ve oradaki URL'yi kopyalayın.

4.Terminal veya Komut İstemcisinde aşağıdaki komutu yapıştırın ve çalıştırın:

```bash
git clone https://github.com/alikaanztrk/GeneticAlgorithm.git
```
İlgili komutu çalıştırdıktan sonra, projenin bir kopyası bilgisayarınıza indirilecektir.

