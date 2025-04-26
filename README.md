# CNN-Resnet
Membangun model klasifikasi gambar berbasis CNN dengan arsitektur ResNet pada dataset MNIST. Model menggunakan residual learning untuk meningkatkan akurasi dan mengatasi vanishing gradient, dengan evaluasi performa menggunakan akurasi data uji.

Pada project ini, akan dibangun dan dilatih model Convolutional Neural Network (CNN) berbasis arsitektur ResNet untuk melakukan klasifikasi gambar angka tangan dari dataset MNIST. Dataset MNIST berisi 70.000 gambar grayscale 28x28 piksel, masing-masing merepresentasikan angka 0 hingga 9.

Tujuan utama project ini adalah:

- Mengimplementasikan konsep residual learning dari ResNet untuk mengatasi masalah vanishing gradient pada jaringan yang dalam.
- Meningkatkan akurasi klasifikasi dibandingkan CNN standar.
- Memahami bagaimana shortcut connection pada ResNet membantu proses training.

Model yang dikembangkan terdiri dari:

- Blok residual sederhana yang berisi convolutional layers, batch normalization, ReLU activation, dan shortcut connections.
- Training dilakukan menggunakan optimizer Adam dan fungsi loss cross-entropy.
- Evaluasi performa model menggunakan metrik akurasi di dataset test MNIST.

Dengan pendekatan ini, diharapkan model mampu mencapai akurasi tinggi (>99%) dalam mengklasifikasikan gambar angka tangan.
