# Ryora — Data Analyst Portfolio

Tiga project analytics **end-to-end**, masing-masing di repo terpisah:
dari data (sintetis terkalibrasi / scraping riil) → SQL → EDA →
statistik → model → dashboard Streamlit → executive report.

---

## 📊 1. POLINDRA PMB Analytics
**[polindra-pmb-analysis](https://github.com/Ryora-max/polindra-pmb-analysis)**

Funnel penerimaan mahasiswa Politeknik Negeri Indramayu 2019–2025:
pendaftar → seleksi → registrasi → performa akademik.

- 17.900 pendaftar · 6.278 mahasiswa · 27.013 KHS (sintetis, seeded)
- ANOVA/chi-square, early-warning dropout (IP sem-1 < 3,0 → 33% recall),
  Random Forest (AUC 0,62 CV), K-Means, forecast, threshold tuning
- Riset jaringan mitra bersumber open-source (evidence matrix ✅/🟡/🔶)

## 💼 2. BeOne ERP Consulting Analytics
**[beone-erp-consulting-analysis](https://github.com/Ryora-max/beone-erp-consulting-analysis)**

Model bisnis konsultan ERP B2B (konteks PT Beone Optima Solusi):
lead → opportunity → implementasi → go-live → managed support.

- 2.900 lead · 1.221 opportunity · 389 proyek · 3.397 tiket (sintetis)
- Win rate per channel (referral 53,5% vs telemarketing 17,1%,
  chi² p=1,4e-12), on-time go-live 59,9%, SLA 88,5%, delay predictor
- Struktur grup, partner/vendor, dan talent pipeline terverifikasi sumber

## 📈 3. Indonesia IT & Analytics Job Market
**[indonesia-job-market-analysis](https://github.com/Ryora-max/indonesia-job-market-analysis)**

Peta pasar kerja digital Indonesia dari **data riil** — Kalibrr API +
LinkedIn guest API (bukan sintetis): data/analytics, software
engineering, infra/DevOps, security, QA, UI/UX, ERP & IT change.

- ~3.500 lowongan di-fetch → 1.524 relevan → ~5.900 baris skill
  terekstrak · 8 domain pasar · 21 keluarga peran
- 69% lowongan di DKI Jakarta · dua platform dua pasar: Kalibrr
  Excel-first (UKM) vs LinkedIn SQL/Python-first (enterprise) ·
  remote ~1% · gaji hanya tampil di 3% lowongan
- Scraping paginasi+dedup+drip-throttle, dirty-data cleaning,
  dokumentasi keterbatasan

---

**Stack:** Python · pandas · SQL/SQLite · scikit-learn · statsmodels ·
Plotly · Streamlit · Jupyter

> Ketiga project didokumentasikan dengan keterbatasannya masing-masing —
> angka di README dihasilkan otomatis oleh `src/key_metrics.py`, bukan
> tulisan tangan.
