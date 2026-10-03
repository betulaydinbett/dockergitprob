# dockergitprob

Bu repo Git, GitHub ve Docker pratiği yapmak için oluşturuldu.

## Hedef

- Ortak projede branch ile çalışma pratiği yapmak
- Commit ve pull request akışını öğrenmek
- Docker temel komutlarını uygulamak
- Docker Compose ile birden fazla servisi çalıştırmak

## Çalışma Akışı

1. Issue seçilir.
2. Yeni branch açılır.
3. Değişiklik yapılır.
4. Commit atılır.
5. Branch GitHub'a push edilir.
6. Pull request açılır.

## Docker Notları

Docker, uygulamaları container denen izole ortamlarda çalıştırmaya yarar.

### Temel Kavramlar

- Image: Uygulamanın çalıştırılmaya hazır paketidir.
- Container: Image'ın çalışan halidir.
- Dockerfile: Kendi image'ını oluşturmak için yazılan tarif dosyasıdır.
- Volume: Container silinse bile veriyi kalıcı tutmaya yarar.
- Network: Container'ların birbirleriyle konuşmasını sağlar.
- Docker Compose: Birden fazla container'ı tek dosya ile çalıştırmaya yarar.

### Temel Komutlar

```bash
docker ps
docker images
docker run hello-world
docker logs container_adi
docker stop container_adi
```
