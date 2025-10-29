# 專案概觀

這是一個 Spring Boot 的 Web 應用程式。它使用 Maven 來管理依賴和建置。主要的應用程式類別是 `com.example.demo.DemoApplication`。

# 建置和執行

## 建置專案

要建置專案，請執行以下指令：

```bash
./mvnw clean install
```

## 執行專案

要執行專案，請執行以下指令：

```bash
./mvnw spring-boot:run
```

## 測試專案

要執行測試，請執行以下指令：

```bash
./mvnw test
```

# 開發慣例

這個專案使用標準的 Spring Boot 專案結構。原始碼位於 `src/main/java`，資源位於 `src/main/resources`。測試程式碼位於 `src/test/java`。