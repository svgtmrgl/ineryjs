# Inery Json RPC 4.Görev
Inery Blockchain'de JSON RPC'yi çağırmak için örnek bir kod

## Bilgiler

JSON RPC Örnek kodu örnek dizinde mevcuttur, [example](https://github.com/herculessx/ineryjs/blob/master/example/) değiştirmeyi deneyebilir ve nasıl çalıştığını anlayabilirsiniz, ayrıca kodunuzu çalıştırabilmek ve değerli sözleşme işlevini çağırabilmek için Hesabınızda Değerli Akıllı Sözleşmeye (Görev 3) sahip olmanız gerekir.


### Prerequisites

 
    Eski Nodejs kaldırın

    ```
    sudo apt-get remove nodejs
    ```

    Curl'ü yükleyin

    ```
    sudo apt-get install curl
    ```

   NodeJS yükleyin

    ```
    curl -fsSL https://deb.nodesource.com/setup_19.x | sudo -E bash - &&\
    sudo apt-get install -y nodejs
    ```

    

 

- NPM Kurulumu

  - Ubuntu

  ```
  sudo apt install npm
  ```


### Kurulum

1. Repoyu klonlayın

   ```
   git clone https://github.com/herculessx/ineryjs.git
   ```

2. Dizini klonlanmış depoya değiştir

   ```
   cd ineryjs
   ```

3. NPM Paket kurulumu

   ```
   npm install
   ```

4. `.env-sample`  `.env` yeniden adlandırın

   ```
   cp .env-sample .env
   ```

5.  ```.env``` bilgileriniz düzenleyin



## Usage

RPC Örneği Çalıştır

```
npm run rpc-example
```
