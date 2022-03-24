---
layout: post
title:  "Linux Terminal Komutları"
date: 2022-03-23
categories: genel
---

Konsol Komutları Linux Sistemlere yeni başlayanlar için zor ve karmaşık görülebilir, fakat bir süre sonra alışıldığında aslında ne kadar kullanışlı olduğu fark edilecektir.

Komut satırında klasörlerde gezinebilir, dosya ve klasör ekleyip, silebilir, içeriğine bakıp, değiştirebilir, sisteminizi günceller, yeni paketler kurabilir ve kaldırabilirsiniz. Bunlardan fazlası da var elbette ama bu yazımızda bazılarına kısaca değinelim.

    echo "tv";

**pwd** hangi dizin (klasör) üzerinde olduğunuzu gösterir.

**ls** dizindeki dosyaları ve dizinleri liste halinde gösterir.

**ls -a** dizindeki dosyaları ve dizinleri (gizliler dahil) liste halinde gösterir.

**ls -l** dizindeki dosyaları ve dizinleri ayrıntılı halde, liste halinde gösterir.

**cd** dizinlerde gezinmek için kullanılır. Mesela cd /etc komutu sizi kök dizindeki etc dizinine gönderir.

**cd ..** bir üst dizine gider.

**mkdir** yeni dizin eklemek için kullanılır.

**mv** dosya taşıma komutu. Ayrıca dosyaya yeni isim vermek için de kullanılır.

**touch** yeni dosya eklemek için kullanılır. Mesela touch test.txt yazarak bir metin dosyası oluşturulur.

**rm** dosya silme için kullanılır.

**rm -r** dizin (içindekilerle beraber) silme komutu.
Önce sudo su, sonra ls, sonra örn. (rm -r dizin)

**cat** dosya içeriğine bakmak için.

    cat dosya.txt

**cp** kopyalama komutu.

**echo** komutuyla ekrana veya bir belgeye yazı girebilirsiniz. Mesela: 

    echo qwe > abc.txt

abc adlı metin dosyası hazırlar ve içine “qwe” yazar,

    echo qwe >> abc.txt

abc adlı metin dosyası içine “qwe” ekler. Tırnak içi kullanımda boşluk kabul edilir:

    echo "merhaba dünya" >> abc.txt

deneyin.

**sudo** geçici olarak root haklarıyla çalışmak için kullanılır.

**man** yardım dosyasını gösterir.

**top** çalışan süreçleri görmenizi sağlar.