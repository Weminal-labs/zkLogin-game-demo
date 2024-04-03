# Next.js with zkLogin and Unity Example
Đây là ví dụ giúp mọi người hiểu cách dùng thư viện`@shinami/nextjs-zklogin`
kết hợp với [Unity SDKs](https://www.npmjs.com/package/react-unity-webgl/v/8.1.7?fbclid=IwAR2sFaZCfVarzqVx_a0_3YwKDHuabNtu7vleYmWv5Qdkx7noTThFV4BrxGA_aem_AWoMs8E7VOZhWqPuaKXzdZ4-c12r9H6ldH90amB-OyN-IpYXEeMWsJNajyLuOnSAEXtwJw5sq__iXYyPrd6N8c34) để giúp user có thể đăng nhập và ký các transaction trên sui. 

Flow hoạt động của app là: 
- user signs trong application bằng gmail
- Sau khi access thành công sẽ redirect về app để người dùng trải nghiệm game 

Ngoài ra vì code chưa được clean lắm nên có một trang protected giúp mọi người hiểu được ví dụ chạy sponsored transaction

## How to use
```
npm installl
```

```
npm run dev
```

Giờ có thể access http://localhost:3000.


# References :
https://docs.shinami.com/docs/sponsored-transaction-typescript-tutorial