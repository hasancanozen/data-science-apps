# Makine Öğrenmesi Projesi

Bu proje, müşteri churn tahmini için end-to-end bir makine öğrenmesi pipeline'ı içerir.

## Proje Yapısı

```
├── data/
│   ├── raw/                 # Ham veri dosyaları
│   ├── processed/           # İşlenmiş veri
│   └── external/            # Harici veri kaynakları
├── notebooks/
│   ├── exploratory/         # Keşifsel veri analizi
│   └── modeling/            # Model geliştirme
├── src/
│   ├── data/                # Veri işleme modülleri
│   ├── features/            # Özellik mühendisliği
│   ├── models/              # Model eğitimi ve değerlendirme
│   └── visualization/       # Görselleştirme araçları
├── tests/                   # Unit testler
├── models/                  # Eğitilmiş model dosyaları
├── reports/                 # Analiz raporları
└── configs/                 # Yapılandırma dosyaları
```

## Kurulum

```bash
pip install -r requirements.txt
```

## Kullanım

1. Veri hazırlama: `python src/data/make_dataset.py`
2. Özellik mühendisliği: `python src/features/build_features.py`
3. Model eğitimi: `python src/models/train_model.py`

## Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin
4. Branch'ınızı push edin
5. Pull Request açın

## Lisans

MIT License
