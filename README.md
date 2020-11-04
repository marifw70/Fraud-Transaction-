# Fraud-Transaction-

## Problem Statement

Era Digital semakin berkembang pesat, terutama bisnis perbankan yang menerapkan sistem digital. namun semakin berkembangnya sistem digital ini, semakin mudah juga orang melakukan fraud pada transaksi. oleh karena itu Bank XYZ meminta tolong untuk Tim Data Scientist Purwadhika untuk mendeteksi Fraud yang terjadi saat transaksi.

## Goals

Melihat pola transaksi yang berpotensi menimbulkan Fraud dan melakukan prediksi terhadap transaksi tersebut

## Conclusion

- Dari 5 jenis transaksi yang dilakukan nasabah, transaksi yang berpotensi mengalami Fraud adalah Cashout dan Transfer dengan total transaksi yang mengalami fraud ada 8197 transaksi
- Waktu yang paling sering terjadi fraud adalah Pukul 02.00 Pagi dan 10.00 pagi
- Jumlah Nominal yang sering kali mengalami Fraud ada diatas 209.000 dengan jumlah kasus sebanyak 5402 kasus
- Saya melakukan Pengujian dengan menggunakan Algoritma Logistic Regression, KNN, Randoforest, dan DT. Dari hasil menggunakan algoritma tersebut, Random Forest menjadi Best Recall Paling baik untuk pengujian di notebook ini, dengan score 99,3899%
