# QIntern 2026: Quantum-Enhanced Neural ODEs and QAOA for Dynamic Energy System Optimization

[![QIntern 2026](https://img.shields.io/badge/Event-QIntern_2026-blue.svg)](https://qworld.net/qintern-2026/)
[![Status: Proposal](https://img.shields.io/badge/Status-Project_Proposal-orange.svg)]()
[![Domain: QML & Optimization](https://img.shields.io/badge/Domain-QML_%7C_Quantum_Optimization-green.svg)]()

## 📌 Proje Özeti (Abstract)

Bu depo, **QIntern 2026** araştırma programı için hazırlanan "Dinamik Enerji Sistemleri Optimizasyonu için Kuantum Destekli Neural ODE'ler ve QAOA" başlıklı proje teklifinin temel dokümanlarını, kavramsal çerçevesini ve ilerleyen süreçteki hibrit kuantum-klasik kod altyapısını içermektedir.

Araştırmanın temel odak noktası, akıllı şebekelerde ve endüstriyel tesislerde karşılaşılan yüksek boyutlu, stokastik enerji yük kaydırma (load-shifting) problemlerini kuantum algoritmalarıyla çözmektir. Bu doğrultuda, geleneksel Karışık Tam Sayılı Doğrusal Programlama (MILP) yöntemlerinin yerini almak üzere **Kuantum Yaklaşık Optimizasyon Algoritması (QAOA)** ve klasik dinamik sistem tahminleyicilerinin yerini almak üzere **Kuantum Neural ODE'ler** ile **Fizik Bilgili Kuantum Sinir Ağları (Q-PINNs)** önerilmektedir.

## 🎯 Temel Bilimsel Hedefler ve Metodoloji

Proje, güncel Noisy Intermediate-Scale Quantum (NISQ) cihazlarının potansiyelini dinamik sistemler teorisiyle birleştirerek aşağıdaki bilimsel katkıları sunmayı hedeflemektedir:

1. **QUBO Formülasyonu ve QAOA Entegrasyonu:** Endüstriyel enerji arbitrajı ve maliyet minimizasyonu problemleri, Kısıtsız İkinci Dereceden İkili Optimizasyon (QUBO) modellerine dönüştürülecek ve QAOA kullanılarak optimize edilecektir.
2. **Kuantum Zaman Serisi Modellemesi:** Termodinamik kısıtlar ve şebeke stres dinamikleri, PQC (Parametreli Kuantum Devreleri) tabanlı Q-PINN'ler ve sürekli zamanlı Neural ODE'ler ile modellenecektir.
3. **Kuantum Pekiştirmeli Öğrenme (QRL) Keşfi:** Geleneksel optimizasyon süreçlerine ek olarak, Markov Karar Süreçleri üzerinden eğitilen Kuantum Derin Q-Ağları (Q-DQN) ile dinamik politika (policy) öğrenimi deneysel olarak test edilecektir.
4. **Donanım Testleri ve Hata Azaltma (Error Mitigation):** Geliştirilen hibrit algoritmalar IBM Quantum gibi gerçek kuantum donanımlarında test edilecek ve donanım gürültüsünün etkilerini minimize etmek için Zero-Noise Extrapolation (ZNE) gibi hata azaltma teknikleri uygulanacaktır.

## 📂 Depo Yapısı (Repository Structure)

*(Not: Bu bölüm, proje takvimi ilerledikçe kodlar eklendikçe aktif hale gelecektir.)*

* `docs/`: Proje teklifi metni (PDF), literatür taraması ve teorik matematiksel ispatlar.
* `notebooks/`: QUBO eşlemeleri, veri gömme (embedding) stratejileri ve QML eğitim adımlarını gösteren etkileşimli Jupyter defterleri.
* `src/`: 
  * `qml_models/`: Q-PINN ve Kuantum Neural ODE mimarileri.
  * `optimization/`: QAOA devreleri ve ceza (penalty) fonksiyonu tanımlamaları.
* `data/`: Endüstriyel enerji tüketim verileri için ön işleme betikleri (Data preprocessing scripts).

## 🛠️ Kullanılacak Teknolojiler (Tech Stack)

* **Kuantum Hesaplama:** Qiskit, PennyLane
* **Makine Öğrenmesi & Diferansiyel Denklemler:** PyTorch, Torchdiffeq
* **Veri Analizi:** NumPy, Pandas, SciPy

## 👨‍💻 Araştırmacı / Yazar

* **Hamza Derim** - *Lisans Öğrencisi, Matematik Bölümü*
* [İletişim veya LinkedIn bağlantınızı buraya ekleyebilirsiniz]

---
*Bu çalışma, kuantum hesaplamanın uygulamalı matematik ve operasyonel araştırma alanlarındaki dönüştürücü gücünü araştırmak amacıyla QIntern 2026 kapsamında önerilmiştir.*
