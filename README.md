This lab demonstrates how I deployed a Blazor web application to Azure App Service and enabled full observability using Application Insights—without modifying the application code. I configured autoinstrumentation at the service level, allowing Azure to collect telemetry data such as failed requests, server response times, and availability metrics.

# Blazor Web App
Web App with:
- Runtime: .NET 8 (LTS)
- OS: Windows

### Overall architecture
<img width="4256" height="2731" alt="rg-WebApp (1)" src="https://github.com/user-attachments/assets/e7213de6-92c3-45fc-bca1-53f10cf032fa" />

### Home
<img width="971" height="477" alt="image" src="https://github.com/user-attachments/assets/8914e003-607b-43cb-a487-75067ac734ec" />

### Counter
<img width="738" height="421" alt="image" src="https://github.com/user-attachments/assets/be5e465f-cce6-4b97-8a47-de0fd9241043" />

### Weather
<img width="1896" height="532" alt="image" src="https://github.com/user-attachments/assets/ca16a89c-baf0-44ab-b10b-6f73bf3208ac" />

### Application insights
<img width="929" height="741" alt="image" src="https://github.com/user-attachments/assets/268e3f5f-aae9-4b8c-997e-d4f9b714b804" />
