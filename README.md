# Rust Roadmap :crab:
* Bu yol haritasının amacı sizleri Rust'ta başlangıç aşamasından ileri seviyeye taşıyacak şekilde dili kavramak ve günümüzdeki bizim amaçladığımız Smart Contractlar ama bunun haricinde Rust'ın kullanılabildiği diğer sektörlere de zemin hazırlamaktır. YTU Blockchain üyeleri tarafından hazırlanan bu Roadmap Rust'ı yeni öğrenecek adaylara öğretici ve pekiştirici bir zemin sunmayı hedeflemektedir. Ayrıca çeşitli etkinlikler ve iş fırsatlarıyla birlikte Rust geliştiricilerini bir çatı altında topladığımız [Whatsapp'taki "Topluluk" kanalımıza](https://www.youtube.com/watch?v=dQw4w9WgXcQ) katılabilirsiniz. Şimdilik birçok kaynak İngilizce olarak yol haritasında yer alsa da gelecek dönemlerde ilgili konu başlıkları altında olabildiğince çok Türkçe kaynağı kendimiz üretmeyi hedefliyoruz.

* Aşağıdaki tablo sırası ile Rust'ta adım adım ilerleyebilmeniz için tasarlanmıştır 👇🏻

## İçerik
| Konu Başlıkları  |
|:------------- |
| [Cargo Package Management](#cargo-package-management)|
| [Common Programming Concepts](#common-programming-concepts)|
| [Ownership](#ownership)|
| [Structs, Enums and Pattern Matching](#structs-enums-and-pattern-matching)|
| [Packages, Crates and Modules](#packages-crates-and-modules)|
| [Common Collections](#common-collections)|
| [Generic Types](#generic-types)|
| [Writing Automated Tests](#writing-automated-tests)|
| [Iterators and Closures](#iterators-and-closures)|

## Blokzincirin Temel Teknolojileri Nedir?
→ Yol haritamızdaki ilk adım blokzincir teknolojisinin temellerini oluşturan yapıtaşlarını öğrenmek olacak.
### Cargo Package Management
* [Rust Book Hello Cargo](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)
* [Rust By Example Cargo](https://doc.rust-lang.org/rust-by-example/cargo.html)
* [**(Video)** Using Cargo](https://www.youtube.com/watch?v=_RfxLg6K9oE&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=2)
* [**(Video)** Getting Started with Rust](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=1)
* [Başa dön ⬆](#i̇çerik)
### Common Programming Concepts
* [Rust Book Common Programming Concepts](https://doc.rust-lang.org/book/ch03-00-common-programming-concepts.html)
* [Rust By Example Variables and Mutability](https://doc.rust-lang.org/rust-by-example/variable_bindings.html)
* [Rust By Example Data Types](https://doc.rust-lang.org/rust-by-example/types.html)
* [Rust By Example Functions](https://doc.rust-lang.org/rust-by-example/fn.html)
* [Rust By Example Comments](https://doc.rust-lang.org/book/ch03-04-comments.html)
* [Rust By Example Control Flow](https://doc.rust-lang.org/rust-by-example/flow_control.html)
* [Rust By Example Expressions](https://doc.rust-lang.org/rust-by-example/expression.html)
* [Rust By Example Primitives](https://doc.rust-lang.org/rust-by-example/primitives.html)
* [**(Video)** Common Programming Concepts](https://www.youtube.com/watch?v=2V0JaMVjzws&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=3)
* [**(Video)** Variables, Constants and Shadowing](https://www.youtube.com/watch?v=xYgfW8cIbMA)
* [**(Video)** Data Types](https://www.youtube.com/watch?v=t047Hseyj_k&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ&index=4)
* [Başa dön ⬆](#i̇çerik)
### Ownership
* [What is Ownership?](https://medium.com/@AtesBagcabasi/ownershipi-anlamak-b82dd9e27aac)
* [Rust Book Ownership](https://doc.rust-lang.org/book/ch04-00-understanding-ownership.html)
* [**(Video)** Understanding Ownership in Rust](https://www.youtube.com/watch?v=VFIOSWy93H0&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=4)
* [**(Video)** Memory Management, Heap & Stake](https://www.youtube.com/watch?v=-6cnnNlAvNk&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ&index=9)
* [**(Video)** Mülkiyet(Ownership)(Türkçe)](https://www.youtube.com/watch?v=_44mSRHKdqI)
* [Başa dön ⬆](#i̇çerik)
### Structs, Enums and Pattern Matching
* [Rust Book Structs](https://doc.rust-lang.org/book/ch05-00-structs.html)
* [Rust Book Enums and Pattern Matching](https://doc.rust-lang.org/book/ch06-00-enums.html)
* [Rust By Example Structs](https://doc.rust-lang.org/rust-by-example/custom_types/structs.html)
* [Rust By Example Enums](https://doc.rust-lang.org/rust-by-example/custom_types/enum.html)
* [**(Video)** Structs in Rust](https://www.youtube.com/watch?v=n3bPhdiJm9I&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=5)
* [**(Video)** Enums and Pattern Matching in Rust](https://www.youtube.com/watch?v=DSZqIJhkNCM&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=6)
* [Başa dön ⬆](#i̇çerik)
### Packages, Crates and Modules
* [Rust Book Managing Growing Projects with Packages, Crates and Modules](https://doc.rust-lang.org/book/ch07-00-managing-growing-projects-with-packages-crates-and-modules.html)
* [Rust By Example Crates](https://doc.rust-lang.org/rust-by-example/crates.html)
* [Rust By Example Modules](https://doc.rust-lang.org/rust-by-example/mod.html)
* [**(Video)** Modules(Basic)](https://www.youtube.com/watch?v=lx5r7yzl1Ps&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=34)
* [**(Video)** Modules(mod Keyword)(Basic)](https://www.youtube.com/watch?v=KDC8epDY5jw&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=36)
* [**(Video)** Module System Explained!](https://www.youtube.com/watch?v=5RPXgDQrjio&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=7)
* [Başa dön ⬆](#i̇çerik)
### Common Collections
* [Rust Book Vectors](https://doc.rust-lang.org/book/ch08-01-vectors.html)
* [Rust Book Strings](https://doc.rust-lang.org/book/ch08-02-strings.html)
* [Rust Book HashMaps](https://doc.rust-lang.org/book/ch08-03-hash-maps.html)
* [**(Video)** Common Collections](https://www.youtube.com/watch?v=Zs-pS-egQSs&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=8)
* [**(Video)** Vectors(Basic)](https://www.youtube.com/watch?v=GcsAQTMYR1M&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=24)
* [**(Video)** Strings(Basic)](https://www.youtube.com/watch?v=IYYlc26vgyU&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=33)
* [**(Video)** HashMaps(Basic)](https://www.youtube.com/watch?v=sTK8fagTsMk&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=31)
* [Başa dön ⬆](#i̇çerik)
