# Dashboard Performa Manufaktur (Manufacturing Performance Dashboard)

Dashboard Power BI interaktif untuk memantau performa manufaktur berdasarkan jenis produk, negara, lokasi gudang, dan waktu. Dashboard ini membantu menjawab di mana biaya produksi terkonsentrasi, produk dan negara mana yang mendorong volume produksi, serta seberapa efisien produksi di tiap negara.

<img src="image/Manufacturing_Dashboard%20(1).png" alt="Manufacturing Performance Dashboard" width="100%">

## Metrik Utama (Kartu KPI)

| Metrik | Deskripsi |
|---|---|
| **Avg. Production Cost** | Rata-rata biaya produksi per catatan produk |
| **Total Quantity Produced** | Total unit yang diproduksi |
| **Avg. Production Cost per Unit** | Rata-rata efisiensi biaya (biaya produksi relatif terhadap jumlah produksi) |

## Visualisasi

- **Production Cost by Product Type**: total biaya produksi untuk setiap kategori produk
- **Production Volume by Country**: porsi total produksi dari tiap negara (donut chart)
- **Product Distribution Across Warehouse Location**: jumlah produksi per wilayah gudang (West, East, North, South)
- **Monthly Production Trend**: jumlah produksi per bulan
- **Total Production by Product Type**: jumlah produksi per kategori produk
- **Cost Efficiency by Country**: rata-rata biaya per unit untuk tiap negara

## Filter

Slicer memungkinkan seluruh dashboard difilter berdasarkan **Year**, **Product Type**, dan **Country**.

## Insight Utama

- **Automobiles dan Textiles** memiliki biaya produksi tertinggi (sekitar $2,2 juta masing-masing), sedangkan **Machinery** terendah (sekitar $1,7 juta).
- **Textiles dan Automobiles** juga unggul dalam volume (sekitar 115 ribu unit masing-masing); Machinery memproduksi paling sedikit (88 ribu).
- **Volume produksi tersebar merata antar negara**, dengan kontribusi sekitar 19% hingga 21% dari total.
- **West** adalah lokasi gudang terbesar (140 ribu unit) dan **South** yang terkecil (124 ribu).
- **Produksi mencapai puncak di bulan Mei (52 ribu unit)** lalu turun tajam dari Oktober hingga Desember (33 hingga 35 ribu).
- **USA memiliki biaya per unit tertinggi ($29,71)** dan **Japan terendah ($22,41)**.

## Tools

- Microsoft Power BI Desktop
- DAX dan Power Query untuk pembersihan data dan kolom kalkulasi

## Struktur Proyek

```
manufacturing-performance-dashboard/
├── Power-BI/
│   └── Manufacturing_performance.pbix   # File laporan Power BI
├── image/
│   └── Manufacturing_Dashboard (1).png  # Tangkapan layar dashboard
└── README.md
```

## Cara Menggunakan

1. Unduh atau clone repositori ini.
2. Buka `Power-BI/Manufacturing_performance.pbix` di [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Gunakan slicer Year, Product Type, dan Country untuk mengeksplorasi data.
