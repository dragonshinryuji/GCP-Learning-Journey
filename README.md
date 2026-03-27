#Project: Setting Up an HTTP Load Balancer on GCP
Deskripsi:
Proyek ini mendemonstrasikan cara mengonfigurasi Application Load Balancer eksternal untuk mendistribusikan trafik ke grup instans backend.
Langkah-langkah yang dilakukan:
Membuat Instance Template untuk web server.
Mengonfigurasi Managed Instance Group (MIG) dengan auto-scaling.
Membuat Health Check untuk memantau status server.
Mengonfigurasi URL Maps dan Target HTTP Proxy untuk routing trafik.
Tools yang digunakan:
Google Cloud Shell (gcloud CLI)
Compute Engine
Cloud Load Balancing
