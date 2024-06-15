# AZURE
## Topic 1
<details>
<summary>접기/펼치기</summary>

### Question 1

### English Version

You have two Hyper-V hosts named Host1 and Host2. Host1 has an Azure virtual machine named VM1 that was deployed by using a custom Azure Resource Manager template.

You need to move VM1 to Host2.

What should you do?

- A. From the Update management blade, click Enable.
- B. From the Overview blade, move VM1 to a different subscription.
- C. From the Redeploy blade, click Redeploy.
- D. From the Profile blade, modify the usage location.

**Correct Answer: C**

When you redeploy a VM, it moves the VM to a new node within the Azure infrastructure and then powers it back on, retaining all your configuration options and associated resources.

Reference: [Redeploy to a new node](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/redeploy-to-new-node)

### Korean Version

Hyper-V 호스트가 Host1과 Host2로 두 개 있습니다. Host1에는 사용자 정의 Azure Resource Manager 템플릿을 사용하여 배포된 Azure 가상 머신 VM1이 있습니다.

VM1을 Host2로 이동해야 합니다.

어떻게 해야 합니까?

- A. 업데이트 관리 블레이드에서 'Enable'을 클릭합니다.
- B. 개요 블레이드에서 VM1을 다른 구독으로 이동합니다.
- C. 재배포 블레이드에서 'Redeploy'를 클릭합니다.
- D. 프로필 블레이드에서 사용 위치를 수정합니다.

**정답: C**

VM을 재배포하면 Azure 인프라 내에서 VM을 새 노드로 이동한 다음 모든 구성 옵션 및 관련 리소스를 유지하면서 다시 전원을 켭니다.

참조: [새 노드로 재배포](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/redeploy-to-new-node)

**Key Terms:**

- Hyper-V hosts
- Azure virtual machine
- Redeploy

---

### Question 2

### English Version

You have downloaded an Azure Resource Manager template to deploy numerous virtual machines. The template is based on a current virtual machine but must be adapted to reference an administrative password.

You need to make sure that the password is not stored in plain text.

You are preparing to create the necessary components to achieve your goal.

Which of the following should you create to achieve your goal? Answer by dragging the correct option from the list to the answer area.

!https://www.examtopics.com/assets/media/exam-media/04273/0000300001.jpg

**Correct Answer:**

!https://prod-files-secure.s3.us-west-2.amazonaws.com/110be694-2804-4b1c-a82e-e03671804704/15aca25c-25fc-4934-81d7-0d695e60e6c7/Untitled.png

### Korean Version

여러 가상 머신을 배포하기 위해 Azure Resource Manager 템플릿을 다운로드했습니다. 이 템플릿은 현재 가상 머신을 기반으로 하지만 관리 비밀번호를 참조하도록 수정해야 합니다.

비밀번호가 일반 텍스트로 저장되지 않도록 해야 합니다.

목표를 달성하기 위해 필요한 구성 요소를 준비하고 있습니다.

목표를 달성하기 위해 다음 중 어떤 것을 생성해야 합니까? 정답을 목록에서 정답 영역으로 드래그하여 선택하십시오.

!https://www.examtopics.com/assets/media/exam-media/04273/0000300001.jpg

**정답:**

!https://prod-files-secure.s3.us-west-2.amazonaws.com/110be694-2804-4b1c-a82e-e03671804704/15aca25c-25fc-4934-81d7-0d695e60e6c7/Untitled.png

**Key Terms:**

- Azure Resource Manager template
- Virtual machines
- Administrative password

---

### Question 3

### English Version

Your company has an Azure Kubernetes Service (AKS) cluster that you manage from an Azure AD-joined device. The cluster is located in a resource group.

Developers have created an application named MyApp. MyApp was packaged into a container image.

You need to deploy the YAML manifest file for the application.

Solution: You install the Azure CLI on the device and run the `kubectl apply -f myapp.yaml` command.

Does this meet the goal?

- A. Yes
- B. No

**Correct Answer: A**

`kubectl apply -f myapp.yaml` applies a configuration change to a resource from a file or stdin.

Reference: [kubectl overview](https://kubernetes.io/docs/reference/kubectl/overview/)

### Korean Version

회사는 Azure AD에 연결된 장치에서 관리하는 Azure Kubernetes Service (AKS) 클러스터를 보유하고 있습니다. 클러스터는 리소스 그룹에 위치해 있습니다.

개발자들은 MyApp이라는 애플리케이션을 만들었습니다. MyApp은 컨테이너 이미지로 패키징되었습니다.

애플리케이션을 위한 YAML 매니페스트 파일을 배포해야 합니다.

솔루션: 장치에 Azure CLI를 설치하고 `kubectl apply -f myapp.yaml` 명령을 실행합니다.

이 목표를 충족합니까?

- A. 예
- B. 아니요

**정답: A**

`kubectl apply -f myapp.yaml` 명령은 파일 또는 stdin에서 리소스에 구성 변경을 적용합니다.

참조: [kubectl 개요](https://kubernetes.io/docs/reference/kubectl/overview/)

**Key Terms:**

- Azure Kubernetes Service (AKS)
- YAML manifest file
- Azure CLI
- kubectl

---

### Question 4

### English Version

Your company has an Azure Kubernetes Service (AKS) cluster that you manage from an Azure AD-joined device. The cluster is located in a resource group.

Developers have created an application named MyApp. MyApp was packaged into a container image.

You need to deploy the YAML manifest file for the application.

Solution: You install the docker client on the device and run the `docker run -it microsoft/azure-cli:0.10.17` command.

Does this meet the goal?

- A. Yes
- B. No

**Correct Answer: B**

### Korean Version

회사는 Azure AD에 연결된 장치에서 관리하는 Azure Kubernetes Service (AKS) 클러스터를 보유하고 있습니다. 클러스터는 리소스 그룹에 위치해 있습니다.

개발자들은 MyApp이라는 애플리케이션을 만들었습니다. MyApp은 컨테이너 이미지로 패키징되었습니다.

애플리케이션을 위한 YAML 매니페스트 파일을 배포해야 합니다.

솔루션: 장치에 도커 클라이언트를 설치하고 `docker run -it microsoft/azure-cli:0.10.17` 명령을 실행합니다.

이 목표를 충족합니까?

- A. 예
- B. 아니요

**정답: B**

**Key Terms:**

- Azure Kubernetes Service (AKS)
- YAML manifest file
- Docker client

---

### Question 5

### English Version

Your company has a web app named WebApp1.

You use the WebJobs SDK to design a triggered App Service background task that automatically invokes a function in the code every time new data is received in a queue.

You are preparing to configure the service processes a queue data item.

Which of the following is the service you should use?

- A. Logic Apps
- B. WebJobs
- C. Flow
- D. Functions

**Correct Answer: B**

Reference: [Azure Functions, Logic Apps, and WebJobs comparison](https://docs.microsoft.com/en-us/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs)

### Korean Version

회사는 WebApp1이라는 웹 앱을 보유하고 있습니다.

WebJobs SDK를 사용하여 큐에 새 데이터가 수신될 때마다 코드에서 함수를 자동으로 호출하는 트리거된 앱 서비스 백그라운드 작업을 설계합니다.

서비스가 큐 데이터 항목을 처리하도록 구성할 준비를 하고 있습니다.

사용해야 하는 서비스는 무엇입니까?

- A. Logic Apps
- B. WebJobs
- C. Flow
- D. Functions

**정답: B**

참조: [Azure Functions, Logic Apps, 및 WebJobs 비교](https://docs.microsoft.com/en-us/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs)

**Key Terms:**

- Web app
- WebJobs SDK
- Triggered App Service background task
- Queue data

---

### Question 6

### English Version

Your company has an Azure subscription.

You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set.

You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance.

Which of the following is the value that you should configure for the platformFaultDomainCount property?

- A. 10
- B. 30
- C. Min Value
- D. Max Value

**Correct Answer: D**

The number of fault domains for managed availability sets varies by region - either two or three per region.

Reference: [

Manage availability](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)

### Korean Version

회사는 Azure 구독을 보유하고 있습니다.

Azure Resource Manager (ARM) 템플릿을 사용하여 구독에 여러 Azure 가상 머신을 배포해야 합니다. 가상 머신은 단일 가용성 세트에 포함됩니다.

ARM 템플릿이 패브릭 장애 또는 유지 관리 시 최대한 많은 가상 머신이 접근 가능하도록 해야 합니다.

platformFaultDomainCount 속성에 대해 설정해야 하는 값은 무엇입니까?

- A. 10
- B. 30
- C. Min Value
- D. Max Value

**정답: D**

관리되는 가용성 세트의 장애 도메인 수는 지역에 따라 다릅니다 - 지역별로 두 개 또는 세 개입니다.

참조: [가용성 관리](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)

**Key Terms:**

- Azure subscription
- Azure virtual machines
- Azure Resource Manager (ARM) templates
- platformFaultDomainCount

---

### Question 7

### English Version

Your company has an Azure subscription.

You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set.

You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance.

Which of the following is the value that you should configure for the platformUpdateDomainCount property?

- A. 10
- B. 20
- C. 30
- D. 40

- Answer
    
    **Correct Answer: D**
    
    Each virtual machine in your availability set is assigned an update domain and a fault domain by the underlying Azure platform. For a given availability set, five non-user-configurable update domains are assigned by default (Resource Manager deployments can then be increased to provide up to 20 update domains) to indicate groups of virtual machines and underlying physical hardware that can be rebooted at the same time.
    
    Reference: [Manage availability](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)
    

### Korean Version

회사는 Azure 구독을 보유하고 있습니다.

Azure Resource Manager (ARM) 템플릿을 사용하여 구독에 여러 Azure 가상 머신을 배포해야 합니다. 가상 머신은 단일 가용성 세트에 포함됩니다.

ARM 템플릿이 패브릭 장애 또는 유지 관리 시 최대한 많은 가상 머신이 접근 가능하도록 해야 합니다.

platformUpdateDomainCount 속성에 대해 설정해야 하는 값은 무엇입니까?

- A. 10
- B. 20
- C. 30
- D. 40

**정답: D**

가용성 세트의 각 가상 머신은 기본 Azure 플랫폼에 의해 업데이트 도메인과 장애 도메인에 할당됩니다. 주어진 가용성 세트에 대해 기본적으로 다섯 개의 사용자 구성 불가능한 업데이트 도메인이 할당되며(리소스 관리자 배포는 최대 20개의 업데이트 도메인까지 증가할 수 있습니다), 이는 동시에 재부팅할 수 있는 가상 머신 및 기본 물리적 하드웨어 그룹을 나타냅니다.

참조: [가용성 관리](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)

**Key Terms:**

- Azure subscription
- Azure virtual machines
- Azure Resource Manager (ARM) templates
- platformUpdateDomainCount

---

### Question 8

### English Version

You are creating an Azure Cosmos DB account that makes use of the SQL API. Data will be added to the account every day by a web application.

You need to ensure that an email notification is sent when information is received from IoT devices, and that compute cost is reduced.

You decide to deploy a function app.

Which of the following should you configure the function app to use? Answer by dragging the correct options from the list to the answer area.

!https://www.examtopics.com/assets/media/exam-media/04273/0000900001.jpg

**Correct Answer:**

!https://www.examtopics.com/assets/media/exam-media/04273/0001000001.jpg

### Korean Version

SQL API를 사용하는 Azure Cosmos DB 계정을 생성하고 있습니다. 매일 웹 애플리케이션을 통해 계정에 데이터가 추가됩니다.

IoT 장치로부터 정보가 수신될 때 이메일 알림이 전송되도록 하고, 컴퓨팅 비용을 절감해야 합니다.

함수 앱을 배포하기로 결정했습니다.

함수 앱을 사용하여 구성해야 하는 것은 무엇입니까? 정답을 목록에서 정답 영역으로 드래그하여 선택하십시오.

!https://www.examtopics.com/assets/media/exam-media/04273/0000900001.jpg

**정답:**

!https://www.examtopics.com/assets/media/exam-media/04273/0001000001.jpg

**Key Terms:**

- Azure Cosmos DB
- SQL API
- Function app

---

### Question 9

### English Version

This question requires that you evaluate the underlined text to determine if it is correct.

Your company has an on-premises deployment of MongoDB, and an Azure Cosmos DB account that makes use of the MongoDB API.

You need to devise a strategy to migrate MongoDB to the Azure Cosmos DB account.

You include the Data Management Gateway tool in your migration strategy.

Instructions: Review the underlined text. If it makes the statement correct, select `No change required.` If the statement is incorrect, select the answer choice that makes the statement correct.

- A. No change required
- B. mongorestore
- C. Azure Storage Explorer
- D. AzCopy

**Correct Answer: B**

Reference: [Migrate MongoDB to Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-migrate) [mongorestore](https://docs.mongodb.com/manual/reference/program/mongorestore/)

### Korean Version

이 질문은 밑줄 친 텍스트를 평가하여 올바른지 여부를 결정해야 합니다.

회사는 온프레미스 MongoDB 배포와 MongoDB API를 사용하는 Azure Cosmos DB 계정을 보유하고 있습니다.

MongoDB를 Azure Cosmos DB 계정으로 마이그레이션하는 전략을 마련해야 합니다.

마이그레이션 전략에 데이터 관리 게이트웨이 도구를 포함합니다.

지침: 밑줄 친 텍스트를 검토하십시오. 진술이 올바른 경우 `No change required.`를 선택하십시오. 진술이 잘못된 경우, 진술을 올바르게 만드는 답변을 선택하십시오.

- A. 변경 필요 없음
- B. mongorestore
- C. Azure Storage Explorer
- D. AzCopy

**정답: B**

참조: [MongoDB를 Azure Cosmos DB로 마이그레이션](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-migrate) [mongorestore](https://docs.mongodb.com/manual/reference/program/mongorestore/)

**Key Terms:**

- MongoDB
- Azure Cosmos DB
- MongoDB API
- Migration

---

### Question 10

### English Version

You are developing an e-Commerce Web App.

You want to use Azure Key Vault to ensure that sign-ins to the e-Commerce Web App are secured by using Azure App Service authentication and Azure Active Directory (AAD).

What should you do on the e-Commerce Web App?

- A. Run the az keyvault secret command.
- B. Enable Azure AD Connect.
- C. Enable Managed Service Identity (MSI).
- D. Create an Azure AD service principal.

**Correct Answer: C**

A managed identity from Azure Active Directory allows your app to easily access other AAD-protected resources such as Azure Key Vault.

Reference: [Managed identity overview](https://docs.microsoft.com/en-us/azure/app-service/overview-managed-identity) [Sample: Access Key Vault](https://docs.microsoft.com/en-us/samples/azure-samples/app-service-msi-keyvault-dotnet/keyvault-msi-appservice-sample/)

### Korean Version

전자상거래 웹 앱을 개발하고 있습니다.

Azure Key Vault를 사용하여 전자상거래 웹 앱의 로그인 보안을 Azure App Service 인증 및 Azure Active Directory (AAD)를 사용하여 보장하려고 합니다.

전자상거래 웹 앱에서 무엇을 해야 합니까?

- A. az keyvault secret 명령을 실행합니다.
- B. Azure AD Connect를 활성화합니다.
- C. 관리 서비스 ID (MSI)를 활성화합니다.
- D. Azure AD 서비스 주체를 만듭니다.

**정답: C**

Azure Active Directory의 관리 ID를 통해 앱이 Azure Key Vault와 같은 다른 AAD 보호 리소스에 쉽게 접근할 수 있습니다.

참조: [관리 ID 개요](https://docs.microsoft.com/en-us/azure/app-service/overview-managed-identity) [샘플: Key Vault 접근](https://docs.microsoft.com/en-us/samples/azure-samples/app-service-msi-keyvault-dotnet/keyvault-msi-appservice-sample/)

**Key Terms:**

- e-Commerce Web App
- Azure Key Vault
- Azure App Service authentication
- Azure Active Directory (AAD)
- Managed Service Identity (MSI)

### Question 11

#### English Version
This question requires that you evaluate the underlined text to determine if it is correct.  
Your Azure Active Directory Azure (Azure AD) tenant has an Azure subscription linked to it.  
Your developer has created a mobile application that obtains Azure AD access tokens using the OAuth 2 implicit grant type.  
The mobile application must be registered in Azure AD.  
You require a redirect URI from the developer for registration purposes.  
Instructions: Review the underlined text. If it makes the statement correct, select `No change is needed.` If the statement is incorrect, select the answer choice that makes the statement correct.
- A. No change required.
- B. a secret
- C. a login hint
- D. a client ID

<details>
<summary>Answer</summary>
    
**Correct Answer: A**  

For Native Applications, you need to provide a Redirect URI, which Azure AD will use to return token responses.  
Reference: [Azure AD OAuth 2.0 Implicit Grant](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code)
</details>

#### Korean Version
이 질문은 밑줄 친 텍스트를 평가하여 올바른지 여부를 결정해야 합니다.  
Azure Active Directory (Azure AD) 테넌트에 Azure 구독이 연결되어 있습니다.  
개발자는 OAuth 2 암시적 승인 유형을 사용하여 Azure AD 액세스 토큰을 얻는 모바일 애플리케이션을 만들었습니다.  
모바일 애플리케이션은 Azure AD에 등록되어야 합니다.  
등록 목적으로 개발자로부터 리디렉션 URI가 필요합니다.  
지침: 밑줄 친 텍스트를 검토하십시오. 진술이 올바른 경우 `No change required.`를 선택하십시오. 진술이 잘못된 경우, 올바른 답변을 선택하십시오.
- A. 변경 필요 없음
- B. 비밀
- C. 로그인 힌트
- D. 클라이언트 ID

<details>
<summary>정답</summary>
    
**정답: A**  

네이티브 애플리케이션의 경우 Azure AD가 토큰 응답을 반환할 리디렉션 URI를 제공해야 합니다.  
참조: [Azure AD OAuth 2.0 암시적 승인](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code)
</details>

**Key Terms:**
- Azure Active Directory (Azure AD)
- OAuth 2 implicit grant
- Redirect URI

---

### Question 12

#### English Version
You are creating an Azure key vault using PowerShell. Objects deleted from the key vault must be kept for a set period of 90 days.  
Which two of the following parameters must be used in conjunction to meet the requirement? (Choose two.)
- A. EnabledForDeployment
- B. EnablePurgeProtection
- C. EnabledForTemplateDeployment
- D. EnableSoftDelete

<details>
<summary>Answer</summary>
    
**Correct Answer: B, D**  

Reference: [Azure Key Vault Soft-Delete](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-ovw-soft-delete)  
[Azure PowerShell New-AzKeyVault](https://docs.microsoft.com/en-us/powershell/module/azurerm.keyvault/new-azurermkeyvault)
</details>

#### Korean Version
PowerShell을 사용하여 Azure 키 자격 증명 모음을 생성하고 있습니다. 키 자격 증명 모음에서 삭제된 객체는 90일 동안 보관되어야 합니다.  
이 요구 사항을 충족하려면 다음 두 가지 매개변수를 함께 사용해야 합니다. (두 가지를 선택하십시오.)
- A. 배포를 위해 활성화됨
- B. 삭제 보호 활성화
- C. 템플릿 배포를 위해 활성화됨
- D. 소프트 삭제 활성화

<details>
<summary>정답</summary>
    
**정답: B, D**  

참조: [Azure 키 자격 증명 모음 소프트 삭제](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-ovw-soft-delete)  
[Azure PowerShell New-AzKeyVault](https://docs.microsoft.com/en-us/powershell/module/azurerm.keyvault/new-azurermkeyvault)
</details>

**Key Terms:**
- Azure key vault
- PowerShell
- EnablePurgeProtection
- EnableSoftDelete

---

### Question 13

#### English Version
You have an Azure Active Directory (Azure AD) tenant.  
You want to implement multi-factor authentication by making use of a conditional access policy. The conditional access policy must be applied to all users when they access the Azure portal.  
Which three settings should you configure? To answer, select the appropriate settings in the answer area.  
NOTE: Each correct selection is worth one point.

**Correct Answer:**

- **Box 1:** The conditional access policy must be applied or assigned to Users and Groups.
- **Box 2:** The conditional access policy must be applied when users access the Azure portal, which is a cloud app. That is: Microsoft Azure Management.
- **Box 3:** Access control must require multi-factor authentication when granting access.

Reference: [Azure AD Conditional Access Policies](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/app-based-mfa)

#### Korean Version
Azure Active Directory (Azure AD) 테넌트가 있습니다.  
조건부 액세스 정책을 사용하여 다단계 인증을 구현하려고 합니다. 조건부 액세스 정책은 Azure 포털에 액세스할 때 모든 사용자에게 적용되어야 합니다.  
어떤 세 가지 설정을 구성해야 합니까? 정답을 선택 영역에서 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

**정답:**

- **Box 1:** 조건부 액세스 정책은 사용자 및 그룹에 적용되거나 할당되어야 합니다.
- **Box 2:** 조건부 액세스 정책은 사용자가 Azure 포털, 즉 Microsoft Azure 관리라는 클라우드 앱에 액세스할 때 적용되어야 합니다.
- **Box 3:** 액세스 제어는 액세스를 허용할 때 다단계 인증이 필요합니다.

참조: [Azure AD 조건부 액세스 정책](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/app-based-mfa)

**Key Terms:**
- Azure Active Directory (Azure AD)
- Multi-factor authentication
- Conditional access policy

---

### Question 14

#### English Version
You manage an Azure SQL database that allows for Azure AD authentication.  
You need to make sure that database developers can connect to the SQL database via Microsoft SQL Server Management Studio (SSMS). You also need to make sure the developers use their on-premises Active Directory account for authentication. Your strategy should allow for authentication prompts to be kept to a minimum.  
Which of the following should you implement?
- A. Azure AD token.
- B. Azure Multi-Factor authentication.
- C. Active Directory integrated authentication.
- D. OATH software tokens.

<details>
<summary>Answer</summary>
    
**Correct Answer: C**  

Azure AD can be the initial Azure AD managed domain. Azure AD can also be an on-premises Active Directory Domain Services that is federated with the Azure AD.  
Using an Azure AD identity to connect using SSMS or SSDT.  
The following procedures show you how to connect to a SQL database with an Azure AD identity using SQL Server Management Studio or SQL Server Database Tools.  
Active Directory integrated authentication:  
Use this method if you are logged in to Windows using your Azure Active Directory credentials from a federated domain.  
1. Start Management Studio or Data Tools and in the Connect to Server (or Connect to Database Engine) dialog box, in the Authentication box, select Active Directory - Integrated. No password is needed or can be entered because your existing credentials will be presented for the connection.  
2. Select the Options button, and on the Connection Properties page, in the Connect to database box, type the name of the user database you want to connect to. (The AD domain name or tenant ID option is only supported for Universal with MFA connection options, otherwise it is greyed out.)
</details>

#### Korean Version
Azure AD 인증을 허용하는 Azure SQL 데이터베이스를 관리합니다.  
데이터베이스 개발자가 Microsoft SQL Server Management Studio (SSMS)를 통해 SQL 데이터베이스에 연결할 수 있도록 해야 합니다. 또한 개발자가 인증을 위해 온프레미스 Active Directory 계정을 사용하도록 해야 합니다. 인증 프롬프트를 최소한으로 유지하는 전략을 마련해야 합니다.  
다음 중 무엇을 구현해야 합니까?
- A. Azure AD 토큰
- B. Azure 다단계 인증
- C. Active Directory 통합 인증
- D. OATH 소프트웨어 토큰

<details>
<summary>정답</summary>
    
**정답: C**  

Azure AD는 초기 Azure AD 관리 도메인이 될 수 있습니다. Azure AD는 또한 Azure AD와 페더레이션된 온프레미스 Active Directory Domain Services가 될 수 있습니다.  
SSMS 또는 SSDT를 사용하여 Azure AD ID로 SQL 데이터베이스에 연결하는 방법은 다음과 같습니다.  
Active Directory

 통합 인증:  
이 방법은 페더레이션된 도메인의 Azure Active Directory 자격 증명을 사용하여 Windows에 로그인한 경우 사용합니다.  
1. Management Studio 또는 Data Tools를 시작하고 서버 연결(또는 데이터베이스 엔진 연결) 대화 상자에서 인증 상자에 Active Directory - Integrated를 선택합니다. 기존 자격 증명이 연결에 사용되므로 비밀번호를 입력할 필요가 없습니다.  
2. 옵션 버튼을 선택하고 연결 속성 페이지에서 연결할 데이터베이스 상자에 연결할 사용자 데이터베이스의 이름을 입력합니다. (AD 도메인

**Key Terms:**
- Azure SQL database
- Azure AD authentication
- Active Directory integrated authentication

</details>

---

### Question 15

#### English Version
You are developing an application to transfer data between on-premises file servers and Azure Blob storage. The application stores keys, secrets, and certificates in Azure Key Vault and makes use of the Azure Key Vault APIs.  
You want to configure the application to allow recovery of an accidental deletion of the key vault or key vault objects for 90 days after deletion.  
What should you do?
- A. Run the Add-AzKeyVaultKey cmdlet.
- B. Run the az keyvault update --enable-soft-delete true --enable-purge-protection true CLI.
- C. Implement virtual network service endpoints for Azure Key Vault.
- D. Run the az keyvault update --enable-soft-delete false CLI.

<details>
<summary>Answer</summary>
    
**Correct Answer: B**  

When soft-delete is enabled, resources marked as deleted resources are retained for a specified period (90 days by default). The service further provides a mechanism for recovering the deleted object, essentially undoing the deletion.  
Purge protection is an optional Key Vault behavior and is not enabled by default. Purge protection can only be enabled once soft-delete is enabled.  
When purge protection is on, a vault or an object in the deleted state cannot be purged until the retention period has passed. Soft-deleted vaults and objects can still be recovered, ensuring that the retention policy will be followed.  
The default retention period is 90 days, but it is possible to set the retention policy interval to a value from 7 to 90 days through the Azure portal. Once the retention policy interval is set and saved it cannot be changed for that vault.  
Reference: [Azure Key Vault Soft-Delete](https://docs.microsoft.com/en-us/azure/key-vault/general/overview-soft-delete)
</details>

#### Korean Version
온프레미스 파일 서버와 Azure Blob 스토리지 간에 데이터를 전송하는 애플리케이션을 개발하고 있습니다. 애플리케이션은 Azure Key Vault에 키, 비밀 및 인증서를 저장하고 Azure Key Vault API를 사용합니다.  
삭제 후 90일 동안 키 자격 증명 모음 또는 키 자격 증명 모음 객체의 실수로 인한 삭제 복구를 허용하도록 애플리케이션을 구성하려고 합니다.  
어떻게 해야 합니까?
- A. Add-AzKeyVaultKey cmdlet 실행.
- B. az keyvault update --enable-soft-delete true --enable-purge-protection true CLI 실행.
- C. Azure Key Vault에 가상 네트워크 서비스 엔드포인트 구현.
- D. az keyvault update --enable-soft-delete false CLI 실행.

<details>
<summary>정답</summary>
    
**정답: B**  

소프트 삭제가 활성화되면 삭제된 리소스로 표시된 리소스가 지정된 기간(기본적으로 90일) 동안 보존됩니다. 서비스는 삭제를 취소하는 기본적으로 삭제된 객체를 복구하는 메커니즘을 추가로 제공합니다.  
삭제 보호는 선택적 키 자격 증명 모음 동작이며 기본적으로 활성화되지 않습니다. 소프트 삭제가 활성화된 후에만 삭제 보호를 활성화할 수 있습니다.  
삭제 보호가 켜지면 보존 기간이 지나기 전까지 삭제된 상태의 자격 증명 모음 또는 객체를 삭제할 수 없습니다. 소프트 삭제된 자격 증명 모음 및 객체는 여전히 복구될 수 있으며 보존 정책이 준수됩니다.  
기본 보존 기간은 90일이지만 Azure 포털을 통해 보존 정책 간격을 7일에서 90일 사이의 값으로 설정할 수 있습니다. 일단 보존 정책 간격이 설정되고 저장되면 해당 자격 증명 모음에 대해 변경할 수 없습니다.  
참조: [Azure Key Vault 소프트 삭제](https://docs.microsoft.com/en-us/azure/key-vault/general/overview-soft-delete)
</details>

**Key Terms:**
- Azure Key Vault
- Soft-delete
- Purge protection

---

### Question 16

#### English Version
You have developed a Web App for your company. The Web App provides services and must run in multiple regions.  
You want to be notified whenever the Web App uses more than 85 percent of the available CPU cores over a 5 minute period. Your solution must minimize costs.  
Which command should you use? To answer, select the appropriate settings in the answer area.  
NOTE: Each correct selection is worth one point.

<details>
<summary>Answer</summary>
    
**Correct Answer:**

Reference: [Azure Monitor Metrics Alerts](https://docs.microsoft.com/sv-se/cli/azure/monitor/metrics/alert)
</details>

#### Korean Version
회사를 위해 웹 앱을 개발했습니다. 웹 앱은 여러 지역에서 실행되어야 합니다.  
웹 앱이 5분 동안 사용 가능한 CPU 코어의 85% 이상을 사용할 때 알림을 받고 싶습니다. 솔루션은 비용을 최소화해야 합니다.  
어떤 명령을 사용해야 합니까? 정답을 선택 영역에서 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

<details>
<summary>정답</summary>
    
**정답:**

참조: [Azure 모니터링 메트릭 경고](https://docs.microsoft.com/sv-se/cli/azure/monitor/metrics/alert)
</details>

**Key Terms:**
- Web App
- CPU usage alert
- Cost minimization

---

### Question 17

#### English Version
You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment.  
You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user.  
Solution: You include the use of Azure Redis Cache in your design.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
    
**Correct Answer: B**

</details>

#### Korean Version
사용자에게 스트리밍 비디오를 제공하는 웹 앱을 구성하고 있습니다. 애플리케이션은 지속적인 통합 및 배포를 사용합니다.  
애플리케이션이 고가용성을 유지하고 사용자의 스트리밍 경험이 일관되도록 해야 합니다. 또한 애플리케이션 데이터를 사용자와 가까운 지리적 위치에 저장하도록 구성하려고 합니다.  
솔루션: Azure Redis Cache를 설계에 포함시킵니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
    
**정답: B**
</details>

**Key Terms:**
- Web app
- Streaming video
- High availability
- Azure Redis Cache

---

### Question 18

#### English Version
You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment.  
You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user.  
Solution: You include the use of an Azure Content Delivery Network (CDN) in your design.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
    
**Correct Answer: A**  

Reference: [Azure CDN](https://docs.microsoft.com/en-in/azure/cdn/)
</details>

#### Korean Version
사용자에게 스트리밍 비디오를 제공하는 웹 앱을 구성하고 있습니다. 애플리케이션은 지속적인 통합 및 배포를 사용합니다.  
애플리케이션이 고가용성을 유지하고 사용자의 스트리밍 경험이 일관되도록 해야 합니다. 또한 애플리케이션 데이터를 사용자와 가까운 지리적 위치에 저장하도록 구성하려고 합니다.  
솔루션: Azure Content Delivery Network (CDN)를 설계에 포함시킵니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
    
**정답: A**  

참조: [Azure CDN](https://docs.microsoft.com/en-in/azure/cdn/)
</details>

**Key Terms:**
- Web app
- Streaming video
- High availability
- Azure Content Delivery Network (CDN)

---

### Question 19

#### English Version
You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment.  
You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user.

  
Solution: You include the use of a Storage Area Network (SAN) in your design.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
    
**Correct Answer: B**
</details>

#### Korean Version
사용자에게 스트리밍 비디오를 제공하는 웹 앱을 구성하고 있습니다. 애플리케이션은 지속적인 통합 및 배포를 사용합니다.  
애플리케이션이 고가용성을 유지하고 사용자의 스트리밍 경험이 일관되도록 해야 합니다. 또한 애플리케이션 데이터를 사용자와 가까운 지리적 위치에 저장하도록 구성하려고 합니다.  
솔루션: 설계에 Storage Area Network (SAN)를 포함시킵니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
    
**정답: B**
</details>

**Key Terms:**
- Web app
- Streaming video
- High availability
- Storage Area Network (SAN)

---

### Question 20

#### English Version
You develop a Web App on a tier D1 app service plan.  
You notice that page load times increase during periods of peak traffic.  
You want to implement automatic scaling when CPU load is above 80 percent. Your solution must minimize costs.  
What should you do first?
- A. Enable autoscaling on the Web App.
- B. Switch to the Premium App Service tier plan.
- C. Switch to the Standard App Service tier plan.
- D. Switch to the Azure App Services consumption plan.

<details>
<summary>Answer</summary>
    
**Correct Answer: C**  

Configure the web app to the Standard App Service Tier. The Standard tier supports auto-scaling, and we should minimize the cost. We can then enable autoscaling on the web app, add a scale rule and add a Scale condition.  
Reference: [Azure App Service Plans](https://azure.microsoft.com/en-us/pricing/details/app-service/plans/)  
[Monitoring Autoscale Get Started](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-autoscale-get-started)
</details>

#### Korean Version
D1 앱 서비스 플랜에서 웹 앱을 개발합니다.  
피크 트래픽 기간 동안 페이지 로드 시간이 증가하는 것을 알게 되었습니다.  
CPU 로드가 80%를 초과할 때 자동 스케일링을 구현하려고 합니다. 솔루션은 비용을 최소화해야 합니다.  
가장 먼저 무엇을 해야 합니까?
- A. 웹 앱에서 자동 스케일링을 활성화합니다.
- B. 프리미엄 앱 서비스 티어 플랜으로 전환합니다.
- C. 표준 앱 서비스 티어 플랜으로 전환합니다.
- D. Azure 앱 서비스 소비 플랜으로 전환합니다.

<details>
<summary>정답</summary>
    
**정답: C**  

웹 앱을 표준 앱 서비스 티어로 구성합니다. 표준 계층은 자동 스케일링을 지원하며 비용을 최소화해야 합니다. 그런 다음 웹 앱에서 자동 스케일링을 활성화하고, 스케일 규칙을 추가하고, 스케일 조건을 추가할 수 있습니다.  
참조: [Azure 앱 서비스 플랜](https://azure.microsoft.com/en-us/pricing/details/app-service/plans/)  
[모니터링 자동 스케일링 시작](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-autoscale-get-started)
</details>

**Key Terms:**
- Web app
- Tier D1 app service plan
- Automatic scaling
- Standard App Service tier plan

### Question 21

#### English Version
Your company's Azure subscription includes an Azure Log Analytics workspace.  
Your company has a hundred on-premises servers that run either Windows Server 2012 R2 or Windows Server 2016 and is linked to the Azure Log Analytics workspace. The Azure Log Analytics workspace is set up to gather performance counters associated with security from these linked servers.  
You must configure alerts based on the information gathered by the Azure Log Analytics workspace.  
You have to make sure that alert rules allow for dimensions, and that alert creation time should be kept to a minimum. Furthermore, a single alert notification must be created when the alert is created and when the alert is resolved.  
You need to make use of the necessary signal type when creating the alert rules.  
Which of the following is the option you should use?
- A. The Activity log signal type.
- B. The Application Log signal type.
- C. The Metric signal type.
- D. The Audit Log signal type.

<details>
<summary>Answer</summary>
  
**Correct Answer: C**  
  
Metric alerts in Azure Monitor provide a way to get notified when one of your metrics crosses a threshold. Metric alerts work on a range of multi-dimensional platform metrics, custom metrics, Application Insights standard and custom metrics.  
Note: Signals are emitted by the target resource and can be of several types: Metric, Activity log, Application Insights, and Log.  
Reference: [Azure Monitor Metric Alerts](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-metric)  
</details>

#### Korean Version
회사의 Azure 구독에는 Azure Log Analytics 작업 영역이 포함되어 있습니다.  
회사는 Windows Server 2012 R2 또는 Windows Server 2016을 실행하는 100대의 온프레미스 서버를 보유하고 있으며 Azure Log Analytics 작업 영역과 연결되어 있습니다. Azure Log Analytics 작업 영역은 이러한 연결된 서버에서 보안과 관련된 성능 카운터를 수집하도록 설정되어 있습니다.  
Azure Log Analytics 작업 영역에서 수집한 정보를 기반으로 경고를 구성해야 합니다.  
경고 규칙이 차원을 허용하고 경고 생성 시간을 최소화해야 합니다. 또한 경고가 생성될 때와 해결될 때 단일 경고 알림이 생성되어야 합니다.  
경고 규칙을 만들 때 필요한 신호 유형을 사용해야 합니다.  
다음 옵션 중 어떤 것을 사용해야 합니까?
- A. 활동 로그 신호 유형
- B. 응용 프로그램 로그 신호 유형
- C. 메트릭 신호 유형
- D. 감사 로그 신호 유형

<details>
<summary>정답</summary>
  
**정답: C**  
  
Azure Monitor의 메트릭 경고는 메트릭이 임계값을 초과할 때 알림을 받는 방법을 제공합니다. 메트릭 경고는 다양한 다차원 플랫폼 메트릭, 사용자 정의 메트릭, Application Insights 표준 및 사용자 정의 메트릭에서 작동합니다.  
참고: 신호는 대상 리소스에 의해 발생하며 여러 유형일 수 있습니다: 메트릭, 활동 로그, Application Insights 및 로그.  
참조: [Azure Monitor 메트릭 경고](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-metric)  
</details>

**Key Terms:**
- Azure Log Analytics
- Metric alerts
- Azure Monitor

---

### Question 22

#### English Version
You are developing a .NET Core MVC application that allows customers to research independent holiday accommodation providers.  
You want to implement Azure Search to allow the application to search the index by using various criteria to locate documents related to accommodation.  
You want the application to allow customers to search the index by using regular expressions.  
What should you do?
- A. Configure the SearchMode property of the SearchParameters class.
- B. Configure the QueryType property of the SearchParameters class.
- C. Configure the Facets property of the SearchParameters class.
- D. Configure the Filter property of the SearchParameters class.

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
  
The SearchParameters.QueryType Property gets or sets a value that specifies the syntax of the search query. The default is 'simple'. Use 'full' if your query uses the Lucene query syntax.  
You can write queries against Azure Search based on the rich Lucene Query Parser syntax for specialized query forms: wildcard, fuzzy search, proximity search, regular expressions are a few examples.  
Reference: [SearchParameters.QueryType Property](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.search.models.searchparameters.querytype)  
</details>

#### Korean Version
독립적인 휴가 숙박 제공업체를 연구할 수 있는 .NET Core MVC 애플리케이션을 개발하고 있습니다.  
애플리케이션에서 다양한 기준을 사용하여 숙박과 관련된 문서를 찾기 위해 인덱스를 검색할 수 있도록 Azure Search를 구현하려고 합니다.  
애플리케이션이 고객이 정규식을 사용하여 인덱스를 검색할 수 있도록 하려고 합니다.  
어떻게 해야 합니까?
- A. SearchParameters 클래스의 SearchMode 속성을 구성합니다.
- B. SearchParameters 클래스의 QueryType 속성을 구성합니다.
- C. SearchParameters 클래스의 Facets 속성을 구성합니다.
- D. SearchParameters 클래스의 Filter 속성을 구성합니다.

<details>
<summary>정답</summary>
  
**정답: B**  
  
SearchParameters.QueryType 속성은 검색 쿼리의 구문을 지정하는 값을 가져오거나 설정합니다. 기본값은 'simple'입니다. 쿼리에 Lucene 쿼리 구문을 사용하는 경우 'full'을 사용합니다.  
Azure Search에 대해 Lucene Query Parser 구문을 기반으로 특수 쿼리 형식을 작성할 수 있습니다: 와일드카드, 퍼지 검색, 근접 검색, 정규식 등이 몇 가지 예입니다.  
참조: [SearchParameters.QueryType 속성](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.search.models.searchparameters.querytype)  
</details>

**Key Terms:**
- .NET Core MVC application
- Azure Search
- SearchParameters.QueryType
- Regular expressions

---

### Question 23

#### English Version
You are a developer at your company.  
You need to update the definitions for an existing Logic App.  
What should you use?
- A. the Enterprise Integration Pack (EIP)
- B. the Logic App Code View
- C. the API Connections
- D. the Logic Apps Designer

<details>
<summary>Answer</summary>
  
**Correct Answer: D**  
</details>

#### Korean Version
당신은 회사의 개발자입니다.  
기존 Logic App의 정의를 업데이트해야 합니다.  
무엇을 사용해야 합니까?
- A. Enterprise Integration Pack (EIP)
- B. Logic App 코드 보기
- C. API 연결
- D. Logic Apps 디자이너

<details>
<summary>정답</summary>
  
**정답: D**  
</details>

**Key Terms:**
- Logic App
- Definitions update
- Logic Apps Designer

---

### Question 24

#### English Version
You are developing a solution for a public-facing API.  
The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end.  
You must configure back-end authentication for the API Management service instance.  
Solution: You configure Basic gateway credentials for the Azure resource.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
</details>

#### Korean Version
공개 API를 위한 솔루션을 개발하고 있습니다.  
API 백엔드는 Azure App Service 인스턴스에 호스팅됩니다. API 백엔드를 위한 RESTful 서비스를 구현했습니다.  
API Management 서비스 인스턴스에 대한 백엔드 인증을 구성해야 합니다.  
솔루션: Azure 리소스에 대해 기본 게이트웨이 자격 증명을 구성합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
  
**정답: B**  
</details>

**Key Terms:**
- Public-facing API
- Azure App Service
- Back-end authentication
- Basic gateway credentials

---

### Question 25

#### English Version
You are developing a solution for a public-facing API.  
The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end.  
You must configure back-end authentication for the API Management service instance.  
Solution: You configure Client cert gateway credentials for the HTTP(s) endpoint.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: A**  
</details>

#### Korean Version
공개 API를 위한 솔루션을 개발하고 있습니다.  
API 백엔드는 Azure App Service 인스턴스에 호스팅됩니다. API 백엔드를 위한 RESTful 서비스를 구현했습니다.  
API Management 서비스 인스턴스에 대한 백엔드 인증을 구성해야 합니다.  
솔루션: HTTP(s) 엔드포인트에 대해 클라이언트 인증서 게이트웨이 자격 증명을 구성합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B.

 아니요

<details>
<summary>정답</summary>
  
**정답: A**  
</details>

**Key Terms:**
- Public-facing API
- Azure App Service
- Back-end authentication
- Client cert gateway credentials

---

### Question 26

#### English Version
You are developing a solution for a public-facing API.  
The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end.  
You must configure back-end authentication for the API Management service instance.  
Solution: You configure Basic gateway credentials for the HTTP(s) endpoint.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
</details>

#### Korean Version
공개 API를 위한 솔루션을 개발하고 있습니다.  
API 백엔드는 Azure App Service 인스턴스에 호스팅됩니다. API 백엔드를 위한 RESTful 서비스를 구현했습니다.  
API Management 서비스 인스턴스에 대한 백엔드 인증을 구성해야 합니다.  
솔루션: HTTP(s) 엔드포인트에 대해 기본 게이트웨이 자격 증명을 구성합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
  
**정답: B**  
</details>

**Key Terms:**
- Public-facing API
- Azure App Service
- Back-end authentication
- Basic gateway credentials

---

### Question 27

#### English Version
You are developing a solution for a public-facing API.  
The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end.  
You must configure back-end authentication for the API Management service instance.  
Solution: You configure Client cert gateway credentials for the Azure resource.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
</details>

#### Korean Version
공개 API를 위한 솔루션을 개발하고 있습니다.  
API 백엔드는 Azure App Service 인스턴스에 호스팅됩니다. API 백엔드를 위한 RESTful 서비스를 구현했습니다.  
API Management 서비스 인스턴스에 대한 백엔드 인증을 구성해야 합니다.  
솔루션: Azure 리소스에 대해 클라이언트 인증서 게이트웨이 자격 증명을 구성합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
  
**정답: B**  
</details>

**Key Terms:**
- Public-facing API
- Azure App Service
- Back-end authentication
- Client cert gateway credentials

---

### Question 28

#### English Version
You are developing a .NET Core MVC application that allows customers to research independent holiday accommodation providers.  
You want to implement Azure Search to allow the application to search the index by using various criteria to locate documents related to accommodation venues.  
You want the application to list holiday accommodation venues that fall within a specific price range and are within a specified distance to an airport.  
What should you do?
- A. Configure the SearchMode property of the SearchParameters class.
- B. Configure the QueryType property of the SearchParameters class.
- C. Configure the Facets property of the SearchParameters class.
- D. Configure the Filter property of the SearchParameters class.

<details>
<summary>Answer</summary>
  
**Correct Answer: D**  
</details>

#### Korean Version
독립적인 휴가 숙박 제공업체를 연구할 수 있는 .NET Core MVC 애플리케이션을 개발하고 있습니다.  
애플리케이션에서 다양한 기준을 사용하여 숙박과 관련된 문서를 찾기 위해 인덱스를 검색할 수 있도록 Azure Search를 구현하려고 합니다.  
애플리케이션이 특정 가격 범위에 속하고 공항에서 지정된 거리 내에 있는 휴가 숙박 장소를 나열하도록 하려고 합니다.  
어떻게 해야 합니까?
- A. SearchParameters 클래스의 SearchMode 속성을 구성합니다.
- B. SearchParameters 클래스의 QueryType 속성을 구성합니다.
- C. SearchParameters 클래스의 Facets 속성을 구성합니다.
- D. SearchParameters 클래스의 Filter 속성을 구성합니다.

<details>
<summary>정답</summary>
  
**정답: D**  
</details>

**Key Terms:**
- .NET Core MVC application
- Azure Search
- Accommodation venues
- Filter property

---

### Question 29

#### English Version
You are a developer at your company.  
You need to edit the workflows for an existing Logic App.  
What should you use?
- A. the Enterprise Integration Pack (EIP)
- B. the Logic App Code View
- C. the API Connections
- D. the Logic Apps Designer

<details>
<summary>Answer</summary>
  
**Correct Answer: D**  
</details>

#### Korean Version
당신은 회사의 개발자입니다.  
기존 Logic App의 워크플로를 편집해야 합니다.  
무엇을 사용해야 합니까?
- A. Enterprise Integration Pack (EIP)
- B. Logic App 코드 보기
- C. API 연결
- D. Logic Apps 디자이너

<details>
<summary>정답</summary>
  
**정답: D**  
</details>

**Key Terms:**
- Logic App
- Workflows edit
- Logic Apps Designer

---

### Question 30

#### English Version
You are a developer for a company that provides a bookings management service in the tourism industry. You are implementing Azure Search for the tour agencies listed in your company's solution.  
You create the index in Azure Search. You now need to use the Azure Search .NET SDK to import the relevant data into the Azure Search service.  
Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions from left to right and arrange them in the correct order.  
Select and Place:

<details>
<summary>Answer</summary>
  
**Correct Answer:**  
1. The index needs to be populated. To do this, we will need a SearchIndexClient. There are two ways to obtain one: by constructing it, or by calling Indexes.GetClient on the SearchServiceClient. Here we will use the first method.  
2. Create the indexBatch with the documents  
   Something like:
   ```csharp
   var hotels = new Hotel[] {
       new Hotel() {
           HotelId = "3",
           BaseRate = 129.99,
           Description = "Close to town hall and the river"
       }
   };
   var batch = IndexBatch.Upload(hotels);
   ```
3. The next step is to populate the newly-created index
   ```csharp
   var batch = IndexBatch.Upload(hotels);
   try {
       indexClient.Documents.Index(batch);
   }
   ```
Reference: [Azure Search .NET SDK](https://docs.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk)
</details>

#### Korean Version
당신은 관광 산업에서 예약 관리 서비스를 제공하는 회사의 개발자입니다. 회사 솔루션에 나열된 여행사를 위해 Azure Search를 구현하고 있습니다.  
Azure Search에서 인덱스를 만듭니다. 이제 Azure Search .NET SDK를 사용하여 관련 데이터를 Azure Search 서비스에 가져와야 합니다.  
어떤 세 가지 작업을 순서대로 수행해야 합니까? 답변하려면 작업 목록에서 적절한 작업을 왼쪽에서 오른쪽으로 이동하여 올바른 순서로 배열하십시오.  
선택하고 배치하십시오:

<details>
<summary>정답</summary>
  
**정답:**  
1. 인덱스를 채워야 합니다. 이렇게 하려면 SearchIndexClient가 필요합니다. 이를 얻는 방법은 두 가지가 있습니다: 생성하거나 SearchServiceClient의 Indexes.GetClient를 호출합니다. 여기서는 첫 번째 방법을 사용합니다.  
2. 문서로 indexBatch를 만듭니다.
   ```csharp
   var hotels = new Hotel[] {
       new Hotel() {
           HotelId = "3",
           BaseRate = 129.99,
           Description = "Close to town hall and the river"
       }
   };
   var batch = IndexBatch.Upload(hotels);
   ```
3. 새로 생성된 인덱스를 채웁니다.
   ```csharp
   var batch = IndexBatch.Upload(hotels);
   try {
       indexClient.Documents.Index(batch);
   }
   ```
참조: [Azure Search .NET SDK](https://docs.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk)
</details>

**Key Terms:**
- Azure Search
- Index
- Azure Search .NET SDK

## Microsoft AZ-204 Exam - Page 5 Questions

### Question 31

#### English Version
You are developing an application that applies a set of governance policies for internal and external services, as well as for applications.  
You develop a stateful ASP.NET Core 2.1 web application named PolicyApp and deploy it to an Azure App Service Web App. The PolicyApp reacts to events from Azure Event Grid and performs policy actions based on those events.  
You have the following requirements:
- Authentication events must be used to monitor users when they sign in and sign out.
- All authentication events must be processed by PolicyApp.
- Sign outs must be processed as fast as possible.

What should you do?
- A. Create a new Azure Event Grid subscription for all authentication events. Use the subscription to process sign-out events.
- B. Create a separate Azure Event Grid handler for sign-in and sign-out events.
- C. Create separate Azure Event Grid topics and subscriptions for sign-in and sign-out events.
- D. Add a subject prefix to sign-out events. Create an Azure Event Grid subscription. Configure the subscription to use the subjectBeginsWith filter.

<details>
<summary>Answer</summary>

**Correct Answer: D**  
</details>

#### Korean Version
내부 및 외부 서비스뿐만 아니라 애플리케이션에 대한 일련의 거버넌스 정책을 적용하는 애플리케이션을 개발하고 있습니다.  
PolicyApp이라는 상태 저장 ASP.NET Core 2.1 웹 애플리케이션을 개발하여 Azure App Service 웹 앱에 배포합니다. PolicyApp은 Azure Event Grid의 이벤트에 반응하고 해당 이벤트를 기반으로 정책 작업을 수행합니다.  
다음 요구 사항이 있습니다:
- 인증 이벤트를 사용하여 사용자가 로그인하고 로그아웃할 때 모니터링해야 합니다.
- 모든 인증 이벤트는 PolicyApp에서 처리해야 합니다.
- 로그아웃은 가능한 한 빨리 처리되어야 합니다.

어떻게 해야 합니까?
- A. 모든 인증 이벤트에 대한 새 Azure Event Grid 구독을 만듭니다. 구독을 사용하여 로그아웃 이벤트를 처리합니다.
- B. 로그인 및 로그아웃 이벤트에 대해 별도의 Azure Event Grid 핸들러를 만듭니다.
- C. 로그인 및 로그아웃 이벤트에 대해 별도의 Azure Event Grid 주제 및 구독을 만듭니다.
- D. 로그아웃 이벤트에 주제 접두사를 추가합니다. Azure Event Grid 구독을 만듭니다. 구독을 subjectBeginsWith 필터를 사용하도록 구성합니다.

<details>
<summary>정답</summary>

**정답: D**  
</details>

**Key Terms:**
- Azure Event Grid
- PolicyApp
- Authentication events

---

### Question 32

#### English Version
You are developing a C++ application that compiles to a native application named process.exe. The application accepts images as input and returns images in one of the following image formats: GIF, PNG, or JPEG.  
You must deploy the application as an Azure Function.  
You need to configure the function and host json files.  
How should you complete the json files? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/f21cfae0-d066-4f90-9fbf-941abbde2bca)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/bbc41a4f-5b78-4e5d-82e9-6c21fe48b162)

- Box 1: "type": "http"
- Box 2: "customHandler": { "description":{
A custom handler is defined by configuring the host.json file with details on how to run the web server via the customHandler section.
The customHandler section points to a target as defined by the defaultExecutablePath.
Example:
"customHandler": {
"description": {
"defaultExecutablePath": "handler.exe"
- Box 3: "enableForwardingHttpRequest": false
Incorrect:
For HTTP-triggered functions with no additional bindings or outputs, you may want your handler to work directly with the HTTP request and response instead of the custom handler request and response payloads. This behavior can be configured in host.json using the enableForwardingHttpRequest setting.
At the root of the app, the host.json file is configured to run handler.exe and enableForwardingHttpRequest is set to true.

- Reference: https://docs.microsoft.com/en-us/azure/azure-functions/functions-custom-handlers

</details>

#### Korean Version
C++ 애플리케이션을 개발 중이며, 이 애플리케이션은 process.exe라는 네이티브 애플리케이션으로 컴파일됩니다. 이 애플리케이션은 이미지를 입력으로 받아 GIF, PNG 또는 JPEG 형식의 이미지로 반환합니다.  
애플리케이션을 Azure Function으로 배포해야 합니다.  
function 및 host json 파일을 구성해야 합니다.  
json 파일을 어떻게 완성해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/f21cfae0-d066-4f90-9fbf-941abbde2bca)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/bbc41a4f-5b78-4e5d-82e9-6c21fe48b162)

</details>

**Key Terms:**
- C++ application
- Azure Function
- JSON configuration

---

### Question 33

#### English Version
You are developing an Azure Static Web app that contains training materials for a tool company. Each tool’s training material is contained in a static web page that is linked from the tool’s publicly available description page.  
A user must be authenticated using Azure AD prior to viewing training.  
You need to ensure that the user can view training material pages after authentication.  
How should you complete the configuration file? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/e669e16a-5072-482c-82ee-cbb881cf365c)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/fdc95924-7b48-4694-a543-7e780235d19d)

</details>

#### Korean Version
도구 회사의 교육 자료를 포함하는 Azure Static Web 앱을 개발하고 있습니다. 각 도구의 교육 자료는 도구의 공개 설명 페이지에서 링크된 정적 웹 페이지에 포함되어 있습니다.  
사용자가 교육을 보기 전에 Azure AD를 통해 인증되어야 합니다.  
사용자가 인증 후 교육 자료 페이지를 볼 수 있도록 해야 합니다.  
구성 파일을 어떻게 완성해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/e669e16a-5072-482c-82ee-cbb881cf365c)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/fdc95924-7b48-4694-a543-7e780235d19d)

</details>

**Key Terms:**
- Azure Static Web app
- Azure AD authentication
- Configuration file

---

### Question 34

#### English Version
You are authoring a set of nested Azure Resource Manager templates to deploy Azure resources. You author an Azure Resource Manager template named mainTemplate.json that contains the following linked templates: linkedTemplate1.json, linkedTemplate2.json.  
You add parameters to a parameters template file named mainTemplate.parameters.json. You save all templates on a local device in the C:\templates\ folder.  
You have the following requirements:
- Store the templates in Azure for later deployment.
- Enable versioning of the templates.
- Manage access to the templates by using Azure RBAC.
- Ensure that users have read-only access to the templates.
- Allow users to deploy the templates.

You need to store the templates in Azure.  
How should you complete the command? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/80fab442-1639-4cbc-95d4-89ba6d4267db)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/37fa49ae-fe52-45a4-9e41-3b6e45d5d2e1)

</details>

#### Korean Version
Azure 리소스를 배포하기 위해 중첩된 Azure Resource Manager 템플릿 세트를 작성하고 있습니다. linkedTemplate1.json 및 linkedTemplate2.json이라는 링크된 템플릿을 포함하는 mainTemplate.json이라는 Azure Resource Manager 템플릿을 작성합니다.  
mainTemplate.parameters.json이라는 매개변수 템플릿 파일에 매개변수를 추가합니다. 모든 템플릿을 C:\templates\ 폴더의 로컬 장치에 저장합니다.  
다음 요구 사항이 있습니다:
- 나중에 배포할 수 있도록 템플릿을 Azure에 저장합니다.
- 템플릿의 버전 관리를 활성화합니다.
- Azure RBAC를 사용하여 템플릿에 대한 액세스를 관리합니다.
- 사용자가 템플릿을 읽기 전용으로 액세스할 수 있도록 합니다.
- 사용자가 템플릿을 배포할 수 있도록 합니다.

템플릿을 Azure에 저장해야

 합니다.  
명령을 어떻게 완성해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/80fab442-1639-4cbc-95d4-89ba6d4267db)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/37fa49ae-fe52-45a4-9e41-3b6e45d5d2e1)

</details>

**Key Terms:**
- Azure Resource Manager templates
- Versioning
- Azure RBAC

---

### Question 35

#### English Version
You are developing a service where customers can report news events from a browser using Azure Web PubSub. The service is implemented as an Azure Function App that uses the JSON WebSocket subprotocol to receive news events.  
You need to implement the bindings for the Azure Function App.  
How should you configure the binding? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/e3b0cbcf-e653-4a5a-a6bb-8a03dc52824c)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/81bdc74a-e283-4ecc-8cff-67bb045b7205)

</details>

#### Korean Version
고객이 브라우저를 사용하여 뉴스 이벤트를 보고할 수 있는 서비스를 개발하고 있습니다. 이 서비스는 뉴스 이벤트를 수신하기 위해 JSON WebSocket 서브프로토콜을 사용하는 Azure Function App으로 구현됩니다.  
Azure Function App에 대한 바인딩을 구현해야 합니다.  
바인딩을 어떻게 구성해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/e3b0cbcf-e653-4a5a-a6bb-8a03dc52824c)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/81bdc74a-e283-4ecc-8cff-67bb045b7205)

</details>

**Key Terms:**
- Azure Web PubSub
- Azure Function App
- JSON WebSocket subprotocol

---

### Question 36

#### English Version
You are building a software-as-a-service (SaaS) application that analyzes DNA data that will run on Azure virtual machines (VMs) in an availability zone. The data is stored on managed disks attached to the VM. The performance of the analysis is determined by the speed of the disk attached to the VM.  
You have the following requirements:
- The application must be able to quickly revert to the previous day’s data if a systemic error is detected.
- The application must minimize downtime in the case of an Azure datacenter outage.

You need to provision the managed disk for the VM to maximize performance while meeting the requirements.  
Which type of Azure Managed Disk should you use? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/104691c6-9bca-4b74-bb11-8b54877be626)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/ea3dac5d-e03f-4a9e-bc1b-3663ea8d5f8e)

</details>

#### Korean Version
Azure 가상 머신(VM)에서 실행되는 DNA 데이터를 분석하는 소프트웨어 서비스(SaaS) 애플리케이션을 구축하고 있습니다. 데이터는 VM에 연결된 관리 디스크에 저장됩니다. 분석 성능은 VM에 연결된 디스크의 속도에 따라 결정됩니다.  
다음 요구 사항이 있습니다:
- 시스템 오류가 감지되면 애플리케이션이 빠르게 이전 날의 데이터로 되돌릴 수 있어야 합니다.
- Azure 데이터센터 장애 시 다운타임을 최소화해야 합니다.

요구 사항을 충족하면서 성능을 최대화하기 위해 VM의 관리 디스크를 프로비저닝해야 합니다.  
어떤 유형의 Azure 관리 디스크를 사용해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/104691c6-9bca-4b74-bb11-8b54877be626)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/ea3dac5d-e03f-4a9e-bc1b-3663ea8d5f8e)

</details>

**Key Terms:**
- Azure Managed Disk
- Premium SSD
- Availability zone

---

### Question 37

#### English Version
You are developing an application that includes two Docker containers.  
The application must meet the following requirements:
- The containers must not run as root.
- The containers must be deployed to Azure Container Instances by using a YAML file.
- The containers must share a lifecycle, resources, local network, and storage volume.
- The storage volume must persist through container crashes.
- The storage volume must be deployed on stop or restart of the containers.

You need to configure Azure Container Instances for the application.  
Which configuration values should you use? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/cebd86b5-9244-4f41-ab97-70ccbfe2ceb7)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/09c2fe91-b30a-48bd-9bdd-4ce2fddb5fbf)

</details>

#### Korean Version
두 개의 Docker 컨테이너를 포함하는 애플리케이션을 개발하고 있습니다.  
애플리케이션은 다음 요구 사항을 충족해야 합니다:
- 컨테이너는 루트로 실행되지 않아야 합니다.
- 컨테이너는 YAML 파일을 사용하여 Azure Container Instances에 배포되어야 합니다.
- 컨테이너는 수명 주기, 리소스, 로컬 네트워크 및 저장소 볼륨을 공유해야 합니다.
- 저장소 볼륨은 컨테이너 충돌 시에도 유지되어야 합니다.
- 저장소 볼륨은 컨테이너 중지 또는 재시작 시에도 배포되어야 합니다.

애플리케이션을 위해 Azure Container Instances를 구성해야 합니다.  
어떤 구성 값을 사용해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/cebd86b5-9244-4f41-ab97-70ccbfe2ceb7)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/09c2fe91-b30a-48bd-9bdd-4ce2fddb5fbf)

</details>

**Key Terms:**
- Docker containers
- Azure Container Instances
- YAML configuration

</details>

## Topic 2
<details>
<summary>접기/펼치기</summary>

### Question 1

#### English Version
You are implementing a software as a service (SaaS) ASP.NET Core web service that will run as an Azure Web App. The web service will use an on-premises SQL Server database for storage. The web service also includes a WebJob that processes data updates. Four customers will use the web service.
- Each instance of the WebJob processes data for a single customer and must run as a singleton instance.
- Each deployment must be tested by using deployment slots prior to serving production data.
- Azure costs must be minimized.
- Azure resources must be located in an isolated network.

You need to configure the App Service plan for the Web App.  
How should you configure the App Service plan? To answer, select the appropriate settings in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/8d7ea73d-1889-439d-a253-8b628f6da114)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/954e54f9-fe44-48f4-bd61-a39a899ad8bb)

Number of VM instances: 4 -
You are not charged extra for deployment slots.

Pricing tier: Isolated -
The App Service Environment (ASE) is a powerful feature offering of the Azure App Service that gives network isolation and improved scale capabilities. It is essentially a deployment of the Azure App Service into a subnet of a customer's Azure Virtual Network (VNet).
Reference:
https://azure.microsoft.com/sv-se/blog/announcing-app-service-isolated-more-power-scale-and-ease-of-use/

</details>

#### Korean Version
Azure Web App으로 실행되는 소프트웨어 서비스(SaaS) ASP.NET Core 웹 서비스를

 구현하고 있습니다. 이 웹 서비스는 저장소로 온프레미스 SQL Server 데이터베이스를 사용합니다. 웹 서비스에는 데이터 업데이트를 처리하는 WebJob도 포함되어 있습니다. 네 명의 고객이 웹 서비스를 사용할 것입니다.
- WebJob의 각 인스턴스는 단일 고객의 데이터를 처리하며 싱글톤 인스턴스로 실행되어야 합니다.
- 각 배포는 프로덕션 데이터를 제공하기 전에 배포 슬롯을 사용하여 테스트해야 합니다.
- Azure 비용을 최소화해야 합니다.
- Azure 리소스는 격리된 네트워크에 있어야 합니다.

웹 앱을 위한 App Service 계획을 구성해야 합니다.  
어떻게 App Service 계획을 구성해야 합니까? 답변하려면 답변 영역에서 적절한 설정을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/8d7ea73d-1889-439d-a253-8b628f6da114)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/954e54f9-fe44-48f4-bd61-a39a899ad8bb)

</details>

**Key Terms:**
- SaaS
- Azure Web App
- App Service plan
- Deployment slots

---

### Question 2

#### English Version
You are a developer for a software as a service (SaaS) company that uses an Azure Function to process orders. The Azure Function currently runs on an Azure Function app that is triggered by an Azure Storage queue.  
You are preparing to migrate the Azure Function to Kubernetes using Kubernetes-based Event Driven Autoscaling (KEDA).  
You need to configure Kubernetes Custom Resource Definitions (CRD) for the Azure Function.  
Which CRDs should you configure? To answer, drag the appropriate CRD types to the correct locations. Each CRD type may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/999869da-1cef-4655-be8c-95de7894db71)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/1b51b317-7e45-4ee1-ae5c-9ddbcf061323)

Box 1: Deployment -
To deploy Azure Functions to Kubernetes use the func kubernetes deploy command has several attributes that directly control how our app scales, once it is deployed to Kubernetes.

Box 2: ScaledObject -
With --polling-interval, we can control the interval used by KEDA to check Azure Service Bus Queue for messages.
Example of ScaledObject with polling interval
apiVersion: keda.k8s.io/v1alpha1
kind: ScaledObject
metadata:
name: transformer-fn
namespace: tt
labels:
deploymentName: transformer-fn
spec:
scaleTargetRef:
deploymentName: transformer-fn
pollingInterval: 5
minReplicaCount: 0
maxReplicaCount: 100

Box 3: Secret -
Store connection strings in Kubernetes Secrets.
Example: to create the Secret in our demo Namespace:
# create the k8s demo namespace
kubectl create namespace tt
# grab connection string from Azure Service Bus
KEDA_SCALER_CONNECTION_STRING=$(az servicebus queue authorization-rule keys list \
-g $RG_NAME \
--namespace-name $SBN_NAME \
--queue-name inbound \
-n keda-scaler \
--query "primaryConnectionString" \
-o tsv)
# create the kubernetes secret
kubectl create secret generic tt-keda-auth \
--from-literal KedaScaler=$KEDA_SCALER_CONNECTION_STRING \
--namespace tt
Reference:
https://www.thinktecture.com/en/kubernetes/serverless-workloads-with-keda/

</details>

#### Korean Version
Azure Storage 큐에 의해 트리거되는 Azure Function 앱에서 현재 실행되고 있는 주문을 처리하는 소프트웨어 서비스(SaaS) 회사의 개발자입니다.  
Azure Function을 Kubernetes 기반 이벤트 구동 자동 확장(KEDA)을 사용하여 Kubernetes로 마이그레이션할 준비를 하고 있습니다.  
Azure Function에 대한 Kubernetes 사용자 정의 리소스 정의(CRD)를 구성해야 합니다.  
어떤 CRD를 구성해야 합니까? 답변하려면 올바른 CRD 유형을 올바른 위치로 드래그하십시오. 각 CRD 유형은 한 번, 여러 번 또는 전혀 사용되지 않을 수 있습니다. 콘텐츠를 보려면 분할 막대를 드래그하거나 스크롤해야 할 수 있습니다.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/999869da-1cef-4655-be8c-95de7894db71)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/1b51b317-7e45-4ee1-ae5c-9ddbcf061323)

</details>

**Key Terms:**
- Azure Function
- Kubernetes
- KEDA
- Custom Resource Definitions (CRD)

---

### Question 3

#### English Version
You are creating a CLI script that creates an Azure web app and related services in Azure App Service. The web app uses the following variables:  

![image](https://github.com/pureliture/pureliture/assets/61732056/5ab959ab-f4df-477a-99f2-480ea95952db)

You need to automatically deploy code from GitHub to the newly created web app.  
How should you complete the script? To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/71e1d45a-d16d-45a0-a008-48c1b8af160c)

<details>
<summary>Answer</summary>

**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/fef9a34a-ef50-43c1-bc36-0caef6d440bc)

Box 1: az appservice plan create
The azure group creates command successfully returns JSON result. Now we can use resource group to create a azure app service plan

Box 2: az webapp create -
Create a new web app..

Box 3: --plan $webappname -
..with the serviceplan we created in step 1.

Box 4: az webapp deployment -
Continuous Delivery with GitHub. Example:
az webapp deployment source config --name firstsamplewebsite1 --resource-group websites--repo-url $gitrepo --branch master --git-token $token
Box 5: --repo-url $gitrepo --branch master --manual-integration
Reference:
https://medium.com/@satish1v/devops-your-way-to-azure-web-apps-with-azure-cli-206ed4b3e9b1


</details>

#### Korean Version
Azure App Service에서 Azure 웹 앱 및 관련 서비스를 만드는 CLI 스크립트를 작성하고 있습니다. 웹 앱은 다음 변수를 사용합니다:

![image](https://github.com/pureliture/pureliture/assets/61732056/5ab959ab-f4df-477a-99f2-480ea95952db)

GitHub에서 새로 생성된 웹 앱으로 코드를 자동으로 배포해야 합니다.  
스크립트를 어떻게 완성해야 합니까? 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/71e1d45a-d16d-45a0-a008-48c1b8af160c)

<details>
<summary>정답</summary>

**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/fef9a34a-ef50-43c1-bc36-0caef6d440bc)

Box 1: az appservice plan create
The azure group creates command successfully returns JSON result. Now we can use resource group to create a azure app service plan

Box 2: az webapp create -
Create a new web app..

Box 3: --plan $webappname -
..with the serviceplan we created in step 1.

Box 4: az webapp deployment -
Continuous Delivery with GitHub. Example:
az webapp deployment source config --name firstsamplewebsite1 --resource-group websites--repo-url $gitrepo --branch master --git-token $token
Box 5: --repo-url $gitrepo --branch master --manual-integration
Reference:
https://medium.com/@satish1v/devops-your-way-to-azure-web-apps-with-azure-cli-206ed4b3e9b1

</details>

**Key Terms:**
- Azure web app
- Azure App Service
- GitHub integration
- CLI script

### Question 4

#### English Version
You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2.  
When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute.  
You need to design the process that starts the photo processing.  
Solution: Trigger the photo processing from Blob storage events.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
You need to catch the triggered event, so move the photo processing to an Azure Function triggered from the blob upload.  
Note: Azure Storage events allow applications to react to events. Common Blob storage event scenarios include image or video processing, search indexing, or any file-oriented workflow.  
Events are pushed using Azure Event Grid to subscribers such as Azure Functions, Azure Logic Apps, or even to your own HTTP listener.  
However, the processing must start in less than one minute.  
Note: Only storage accounts of kind StorageV2 (general purpose v2) and BlobStorage support event integration. Storage (general purpose v1) does not support integration with Event Grid.  
Reference: [Azure Storage Event Overview](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-overview)
</details>

#### Korean Version
사진을 관리하기 위한 소프트웨어 서비스(SaaS) 제공을 개발합니다. 사용자는 사진을 웹 서비스에 업로드하고, 웹 서비스는 사진을 Azure Storage Blob 스토리지에 저장합니다. 스토리지 계정 유형은 General-purpose V2입니다.  
사진이 업로드되면 모바일 친화적인 버전의 이미지를 생성하고 저장해야 합니다. 모바일 친화적인 버전의 이미지를 생성하는 프로세스는 1분 이내에 시작해야 합니다.  
사진 처리를 시작하는 프로세스를 설계해야 합니다.  
해결책: Blob 스토리지 이벤트에서 사진 처리를 트리거합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
  
**정답: B**  
트리거된 이벤트를 잡아야 하므로, Blob 업로드에서 트리거된 Azure Function으로 사진 처리를 이동해야 합니다.  
참고: Azure Storage 이벤트를 사용하면 애플리케이션이 이벤트에 반응할 수 있습니다. 일반적인 Blob 스토리지 이벤트 시나리오에는 이미지 또는 비디오 처리, 검색 인덱싱 또는 파일 지향 워크플로가 포함됩니다.  
이벤트는 Azure Event Grid를 사용하여 Azure Functions, Azure Logic Apps 또는 사용자 자신의 HTTP 리스너와 같은 구독자에게 푸시됩니다.  
그러나 처리는 1분 이내에 시작되어야 합니다.  
참고: StorageV2(일반 목적 v2) 및 BlobStorage 유형의 스토리지 계정만 이벤트 통합을 지원합니다. Storage(일반 목적 v1)는 Event Grid와의 통합을 지원하지 않습니다.  
참조: [Azure Storage 이벤트 개요](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-overview)
</details>

**Key Terms:**
- SaaS
- Azure Storage Blob
- Azure Event Grid
- Azure Functions

---

### Question 5

#### English Version
You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot.  
You need to ensure that scripts run and resources are available before a swap operation occurs.  
Solution: Update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts.  
Does the solution meet the goal?
- A. No
- B. Yes

<details>
<summary>Answer</summary>
  
**Correct Answer: A**  
Specify custom warm-up.  
Some apps might require custom warm-up actions before the swap. The applicationInitialization configuration element in web.config lets you specify custom initialization actions. The swap operation waits for this custom warm-up to finish before swapping with the target slot. Here's a sample web.config fragment.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
Reference: [Azure App Service Deployment Slots](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)
</details>

#### Korean Version
Windows에서 호스팅되는 개발 슬롯이라는 배포 슬롯에 Azure App Service API 앱을 개발하고 배포합니다. Testing 및 Production이라는 추가 배포 슬롯을 만듭니다. Production 배포 슬롯에서 자동 전환을 활성화합니다.  
전환 작업이 발생하기 전에 스크립트가 실행되고 리소스가 사용 가능해야 합니다.  
해결책: 웹.config 파일을 업데이트하여 applicationInitialization 구성 요소를 포함합니다. 스크립트를 실행하기 위한 사용자 지정 초기화 작업을 지정합니다.  
이 솔루션이 목표를 충족합니까?
- A. 아니요
- B. 예

<details>
<summary>정답</summary>
  
**정답: A**  
사용자 지정 워밍업을 지정하십시오.  
일부 앱은 전환 전에 사용자 지정 워밍업 작업이 필요할 수 있습니다. 웹.config의 applicationInitialization 구성 요소를 사용하면 사용자 지정 초기화 작업을 지정할 수 있습니다. 전환 작업은 이 사용자 지정 워밍업이 완료될 때까지 기다린 후 대상 슬롯과 전환됩니다. 다음은 샘플 웹.config 조각입니다.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
참조: [Azure App Service 배포 슬롯](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)
</details>

**Key Terms:**
- Azure App Service
- Deployment slots
- Auto swap
- Custom warm-up

---

### Question 6

#### English Version
You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot.  
You need to ensure that scripts run and resources are available before a swap operation occurs.  
Solution: Enable auto swap for the Testing slot. Deploy the app to the Testing slot.  
Does the solution meet the goal?
- A. No
- B. Yes

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
Instead, update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts.  
Note: Some apps might require custom warm-up actions before the swap. The applicationInitialization configuration element in web.config lets you specify custom initialization actions. The swap operation waits for this custom warm-up to finish before swapping with the target slot. Here's a sample web.config fragment.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
Reference: [Azure App Service Deployment Slots](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)
</details>

#### Korean Version
Windows에서 호스팅되는 개발 슬롯이라는 배포 슬롯에 Azure App Service API 앱을 개발하고 배포합니다. Testing 및 Production이라는 추가 배포 슬롯을 만듭니다. Production 배포 슬롯에서 자동 전환을 활성화합니다.  
전환 작업이 발생하기 전에 스크립트가 실행되고 리소스가 사용 가능해야 합니다.  
해결책: Testing 슬롯에 대한 자동 전환을 활성화합니다. 앱을 Testing 슬롯에 배포합니다.  
이 솔루션이 목표를 충족합니까?
- A. 아니요
- B. 예

<details>
<summary>정답</summary>
  
**정답: B**  
대신, 웹.config 파일을 업데이트하여 applicationInitialization 구성 요소를 포함합니다. 스크립트를 실행하기 위한 사용자 지정 초기화 작업을 지정합니다.  
참고: 일부 앱은 전환 전에 사용자 지정 워밍업 작업이 필요할 수 있습니다. 웹.config의 applicationInitialization 구성 요소를 사용하면 사용자 지정 초기화 작업을 지정할 수 있습니다. 전환 작업은 이 사용자 지정 워밍업이 완료될 때까지 기다린 후 대상 슬롯과 전환됩니다. 다음은 샘플 웹.config 조각입니다.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
참조: [Azure App Service 배포 슬롯](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)


</details>

**Key Terms:**
- Azure App Service
- Deployment slots
- Auto swap
- Custom warm-up

---

### Question 7

#### English Version
You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot.  
You need to ensure that scripts run and resources are available before a swap operation occurs.  
Solution: Disable auto swap. Update the app with a method named `statuscheck` to run the scripts. Re-enable auto swap and deploy the app to the Production slot.  
Does the solution meet the goal?
- A. No
- B. Yes

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
Instead, update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts.  
Note: Some apps might require custom warm-up actions before the swap. The applicationInitialization configuration element in web.config lets you specify custom initialization actions. The swap operation waits for this custom warm-up to finish before swapping with the target slot. Here's a sample web.config fragment.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
Reference: [Azure App Service Deployment Slots](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)
</details>

#### Korean Version
Windows에서 호스팅되는 개발 슬롯이라는 배포 슬롯에 Azure App Service API 앱을 개발하고 배포합니다. Testing 및 Production이라는 추가 배포 슬롯을 만듭니다. Production 배포 슬롯에서 자동 전환을 활성화합니다.  
전환 작업이 발생하기 전에 스크립트가 실행되고 리소스가 사용 가능해야 합니다.  
해결책: 자동 전환을 비활성화합니다. 스크립트를 실행하기 위해 `statuscheck`라는 메서드를 사용하여 앱을 업데이트합니다. 자동 전환을 다시 활성화하고 앱을 Production 슬롯에 배포합니다.  
이 솔루션이 목표를 충족합니까?
- A. 아니요
- B. 예

<details>
<summary>정답</summary>
  
**정답: B**  
대신, 웹.config 파일을 업데이트하여 applicationInitialization 구성 요소를 포함합니다. 스크립트를 실행하기 위한 사용자 지정 초기화 작업을 지정합니다.  
참고: 일부 앱은 전환 전에 사용자 지정 워밍업 작업이 필요할 수 있습니다. 웹.config의 applicationInitialization 구성 요소를 사용하면 사용자 지정 초기화 작업을 지정할 수 있습니다. 전환 작업은 이 사용자 지정 워밍업이 완료될 때까지 기다린 후 대상 슬롯과 전환됩니다. 다음은 샘플 웹.config 조각입니다.  
```xml
<system.webServer>
  <applicationInitialization>
    <add initializationPage="/" hostName="[app hostname]" />
    <add initializationPage="/Home/About" hostName="[app hostname]" />
  </applicationInitialization>
</system.webServer>
```
참조: [Azure App Service 배포 슬롯](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#troubleshoot-swaps)
</details>

**Key Terms:**
- Azure App Service
- Deployment slots
- Auto swap
- Custom warm-up

---

### Question 8

#### English Version
You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2.  
When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute.  
You need to design the process that starts the photo processing.  
Solution: Convert the Azure Storage account to a BlockBlobStorage storage account.  
Does the solution meet the goal?
- A. Yes
- B. No

<details>
<summary>Answer</summary>
  
**Correct Answer: B**  
Not necessary to convert the account, instead move photo processing to an Azure Function triggered from the blob upload.  
Azure Storage events allow applications to react to events. Common Blob storage event scenarios include image or video processing, search indexing, or any file-oriented workflow.  
Note: Only storage accounts of kind StorageV2 (general purpose v2) and BlobStorage support event integration. Storage (general purpose v1) does not support integration with Event Grid.  
Reference: [Azure Storage Event Overview](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-overview)
</details>

#### Korean Version
사진을 관리하기 위한 소프트웨어 서비스(SaaS) 제공을 개발합니다. 사용자는 사진을 웹 서비스에 업로드하고, 웹 서비스는 사진을 Azure Storage Blob 스토리지에 저장합니다. 스토리지 계정 유형은 General-purpose V2입니다.  
사진이 업로드되면 모바일 친화적인 버전의 이미지를 생성하고 저장해야 합니다. 모바일 친화적인 버전의 이미지를 생성하는 프로세스는 1분 이내에 시작해야 합니다.  
사진 처리를 시작하는 프로세스를 설계해야 합니다.  
해결책: Azure Storage 계정을 BlockBlobStorage 스토리지 계정으로 변환합니다.  
이 솔루션이 목표를 충족합니까?
- A. 예
- B. 아니요

<details>
<summary>정답</summary>
  
**정답: B**  
계정을 변환할 필요가 없으며, 대신 Blob 업로드에서 트리거된 Azure Function으로 사진 처리를 이동합니다.  
Azure Storage 이벤트를 사용하면 애플리케이션이 이벤트에 반응할 수 있습니다. 일반적인 Blob 스토리지 이벤트 시나리오에는 이미지 또는 비디오 처리, 검색 인덱싱 또는 파일 지향 워크플로가 포함됩니다.  
참고: StorageV2(일반 목적 v2) 및 BlobStorage 유형의 스토리지 계정만 이벤트 통합을 지원합니다. Storage(일반 목적 v1)는 Event Grid와의 통합을 지원하지 않습니다.  
참조: [Azure Storage 이벤트 개요](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-overview)
</details>

**Key Terms:**
- SaaS
- Azure Storage Blob
- BlockBlobStorage
- Azure Functions

---

### Question 9

#### English Version
You are developing an Azure Web App. You configure TLS mutual authentication for the web app.  
You need to validate the client certificate in the web app. To answer, select the appropriate options in the answer area.  
NOTE: Each correct selection is worth one point.

![image](https://github.com/pureliture/pureliture/assets/61732056/655e6bde-3acf-4fba-97fb-b7eea9b5aad3)

<details>
<summary>Answer</summary>
  
**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/3c0a02e7-7181-428c-b437-01ca476c2b48)

Accessing the client certificate from App Service.  
If you are using ASP.NET and configure your app to use client certificate authentication, the certificate will be available through the HttpRequest.ClientCertificate property. For other application stacks, the client cert will be available in your app through a base64 encoded value in the "X-ARR-ClientCert" request header. Your application can create a certificate from this value and then use it for authentication and authorization purposes in your application.  
Reference: [Azure TLS Mutual Authentication](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-configure-tls-mutual-auth)
</details>

#### Korean Version
Azure Web 앱을 개발 중입니다. 웹 앱에 대해 TLS 상호 인증을 구성합니다.  
웹 앱에서 클라이언트 인증서를 검증해야 합니다. 답변하려면 답변 영역에서 적절한 옵션을 선택하십시오.  
참고: 각 올바른 선택은 1점입니다.

![image](https://github.com/pureliture/pureliture/assets/61732056/655e6bde-3acf-4fba-97fb-b7eea9b5aad3)

<details>
<summary>정답</summary>
  
**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/3c0a02e7-7181-428c-b437-01ca476c2b48)

App Service에서 클라이언트 인증서에 액세스합니다.  
ASP.NET을 사용하고 앱을 클라이언트 인증서 인증을 사용하도록 구성한 경우 인증서는 HttpRequest.ClientCertificate 속성을 통해 사용할 수 있습니다. 다른 애플리케이션 스택의 경우 클라이언트 인증서는 "X-ARR-ClientCert" 요청 헤더의 base64 인코딩된 값으로 앱에서 사용할 수 있습니다. 이 값을 사용하여 인증서를 생성한 다음 애플리케이션에서 인증 및 권한 부여 목적으로 사용할 수 있습니다.  
참조: [Azure TLS 상호 인증](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-configure-tls-mutual-auth)
</details>

**Key Terms:**
- Azure Web App
- TLS mutual authentication
- Client certificate validation

---

### Question 10

#### English Version
You are developing a Docker/Go using Azure App Service Web App for Containers. You plan to run the container in an App Service on Linux. You identify a Docker container image to use.  
None of your current resource groups reside in a location that supports Linux. You must minimize the number of resource groups required.  
You need to create the application and perform an initial deployment.  
Which three Azure CLI commands should you use to develop the solution? To answer, move the appropriate commands from the list of commands to the answer area and arrange them

 in the correct order.

![image](https://github.com/pureliture/pureliture/assets/61732056/46ca755b-b28a-470d-a423-0c3fbeb258c9)

<details>
<summary>Answer</summary>
  
**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/c464cbcf-8c8e-4465-9f3b-8afc7802a68d)

You can host native Linux applications in the cloud by using Azure Web Apps. To create a Web App for Containers, you must run Azure CLI commands that create a group, then a service plan, and finally the web app itself.  
Step 1: `az group create`  
In the Cloud Shell, create a resource group with the az group create command.  
Step 2: `az appservice plan create`  
In the Cloud Shell, create an App Service plan in the resource group with the az appservice plan create command.  
Step 3: `az webapp create`  
In the Cloud Shell, create a web app in the myAppServicePlan App Service plan with the az webapp create command. Don't forget to replace with a unique app name, and <docker-ID> with your Docker ID.  
Reference: [Azure Web Apps for Containers](https://docs.microsoft.com/mt-mt/azure/app-service/containers/quickstart-docker-go?view=sql-server-ver15)
</details>

#### Korean Version
Docker/Go를 사용하여 Azure App Service Web App for Containers를 개발 중입니다. 컨테이너를 Linux의 App Service에서 실행할 계획입니다. 사용할 Docker 컨테이너 이미지를 식별합니다.  
현재 리소스 그룹 중 Linux를 지원하는 위치에 있는 리소스 그룹이 없습니다. 필요한 리소스 그룹의 수를 최소화해야 합니다.  
애플리케이션을 만들고 초기 배포를 수행해야 합니다.  
솔루션을 개발하기 위해 어떤 세 가지 Azure CLI 명령을 사용해야 합니까? 답변하려면 명령 목록에서 적절한 명령을 답변 영역으로 이동하여 올바른 순서로 배열하십시오.

![image](https://github.com/pureliture/pureliture/assets/61732056/46ca755b-b28a-470d-a423-0c3fbeb258c9)

<details>
<summary>정답</summary>
  
**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/c464cbcf-8c8e-4465-9f3b-8afc7802a68d)

Azure Web Apps를 사용하여 클라우드에서 네이티브 Linux 애플리케이션을 호스팅할 수 있습니다. 컨테이너용 웹 앱을 만들려면 리소스 그룹을 만들고, 서비스 계획을 만들고, 마지막으로 웹 앱을 만드는 Azure CLI 명령을 실행해야 합니다.  
1단계: `az group create`  
Cloud Shell에서 az group create 명령을 사용하여 리소스 그룹을 만듭니다.  
2단계: `az appservice plan create`  
Cloud Shell에서 az appservice plan create 명령을 사용하여 리소스 그룹에 App Service 계획을 만듭니다.  
3단계: `az webapp create`  
Cloud Shell에서 az webapp create 명령을 사용하여 myAppServicePlan App Service 계획에 웹 앱을 만듭니다. 고유한 앱 이름으로 교체하고 <docker-ID>를 Docker ID로 교체하는 것을 잊지 마십시오.  
참조: [Azure Web Apps for Containers](https://docs.microsoft.com/mt-mt/azure/app-service/containers/quickstart-docker-go?view=sql-server-ver15)
</details>

**Key Terms:**
- Azure App Service
- Docker
- CLI commands
- Resource group

---

### Question 11

#### English Version
Fourth Coffee has an ASP.NET Core web app that runs in Docker. The app is mapped to the www.fourthcoffee.com domain.  
Fourth Coffee is migrating this application to Azure.  
You need to provision an App Service Web App to host this docker image and map the custom domain to the App Service web app.  
A resource group named FourthCoffeePublicWebResourceGroup has been created in the WestUS region that contains an App Service Plan named AppServiceLinuxDockerPlan.  
Which order should the CLI commands be used to develop the solution? To answer, move all of the Azure CLI commands from the list of commands to the answer area and arrange them in the correct order.

![image](https://github.com/pureliture/pureliture/assets/61732056/1d60d539-c559-4770-bfb1-b03bf5ec015e)

<details>
<summary>Answer</summary>
  
**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/75b164fd-e98c-4680-bdb3-521f423f110c)

Step 1: `#bin/bash`  
The appName is used when the webapp-name is created in step 2.  
Step 2: `az webapp create`  
Create a web app. In the Cloud Shell, create a web app in the myAppServicePlan App Service plan with the az webapp create command.  
Step 3: `az webapp config container set`  
In Create a web app, you specified an image on Docker Hub in the az webapp create command. This is good enough for a public image. To use a private image, you need to configure your Docker account ID and password in your Azure web app.  
Step 4: `az webapp config hostname add`  
The webapp-name is used when the webapp is created in step 2.  
In the Cloud Shell, follow the az webapp create command with az webapp config container set.  
Reference: [Azure App Service Web App for Containers](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image) [Azure App Service Custom Domain](https://docs.microsoft.com/en-us/azure/app-service/scripts/cli-configure-custom-domain)
</details>

#### Korean Version
Fourth Coffee에는 Docker에서 실행되는 ASP.NET Core 웹 앱이 있습니다. 앱은 www.fourthcoffee.com 도메인에 매핑됩니다.  
Fourth Coffee는 이 애플리케이션을 Azure로 마이그레이션하고 있습니다.  
이 Docker 이미지를 호스팅하기 위해 App Service Web App을 프로비저닝하고 사용자 지정 도메인을 App Service 웹 앱에 매핑해야 합니다.  
WestUS 지역에 FourthCoffeePublicWebResourceGroup이라는 리소스 그룹이 생성되어 있으며 AppServiceLinuxDockerPlan이라는 App Service 계획이 포함되어 있습니다.  
솔루션을 개발하기 위해 CLI 명령을 어떤 순서로 사용해야 합니까? 답변하려면 명령 목록의 모든 Azure CLI 명령을 답변 영역으로 이동하여 올바른 순서로 배열하십시오.

![image](https://github.com/pureliture/pureliture/assets/61732056/1d60d539-c559-4770-bfb1-b03bf5ec015e)

<details>
<summary>정답</summary>
  
**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/75b164fd-e98c-4680-bdb3-521f423f110c)

1단계: `#bin/bash`  
웹앱 이름이 2단계에서 생성될 때 사용됩니다.  
2단계: `az webapp create`  
웹 앱을 만듭니다. Cloud Shell에서 az webapp create 명령을 사용하여 myAppServicePlan App Service 계획에 웹 앱을 만듭니다.  
3단계: `az webapp config container set`  
웹 앱을 만들 때 az webapp create 명령에서 Docker Hub의 이미지를 지정했습니다. 공개 이미지에 대해서는 이것으로 충분합니다. 비공개 이미지를 사용하려면 Azure 웹 앱에서 Docker 계정 ID와 비밀번호를 구성해야 합니다.  
4단계: `az webapp config hostname add`  
웹앱 이름이 2단계에서 생성될 때 사용됩니다.  
Cloud Shell에서 az webapp create 명령 뒤에 az webapp config container set 명령을 따르십시오.  
참조: [Azure App Service Web App for Containers](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image) [Azure App Service Custom Domain](https://docs.microsoft.com/en-us/azure/app-service/scripts/cli-configure-custom-domain)
</details>

**Key Terms:**
- Azure App Service
- Docker
- CLI commands
- Custom domain

---

### Question 12

#### English Version
You are developing a serverless Java application on Azure. You create a new Azure Key Vault to work with secrets from a new Azure Functions application.  
The application must meet the following requirements:
- Reference the Azure Key Vault without requiring any changes to the Java code.
- Dynamically add and remove instances of the Azure Functions host based on the number of incoming application events.
- Ensure that instances are perpetually warm to avoid any cold starts.
- Connect to a VNet.
- Authentication to the Azure Key Vault instance must be removed if the Azure Function application is deleted.

You need to grant the Azure Functions application access to the Azure Key Vault.  
Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order.

![image](https://github.com/pureliture/pureliture/assets/61732056/9b8c0d9d-92f5-4b0e-af48-28eeadb9bb7e)

<details>
<summary>Answer</summary>
  
**Correct Answer:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/2b4c5366-eaa8-4246-a279-1196046ecd93)

Step 1: Create the Azure Functions app with a Consumption plan type.
Use the Consumption plan for serverless.
Step 2: Create a system-assigned managed identity for the application.
Create a system-assigned managed identity for your application. Key Vault references currently only support system-assigned managed identities. User-assigned identities cannot be used.
Step 3: Create an access policy in Key Vault for the application identity.
Create an access policy in Key Vault for the application identity you created earlier. Enable the "Get" secret permission on this policy. Do not configure the "authorized application" or applicationId settings, as this is not compatible with a managed identity.
Reference: Azure App Service Key Vault References

</details>

#### Korean Version
Azure에서 서버리스 Java 애플리케이션을 개발 중입니다. 새로운 Azure Functions 애플리케이션에서 비밀을 처리하기 위해 새로운 Azure Key Vault를 만듭니다.  
애플리케이션은 다음 요구 사항을 충족해야 합니다:
- Java 코드를 변경하지 않고 Azure Key Vault를 참조합니다.
- 들어오는 애플리케이션 이벤트 수에 따라 Azure Functions 호스트 인스턴스를 동적으로 추가 및 제거합니다.
- 콜드 스타트를 방지하기 위해 인스턴스가 영구적으로 따뜻하게 유지됩니다.
- VNet에 연결합니다.
- Azure Functions 애플리케이션이 삭제된 경우 Azure Key Vault 인스턴스에 대한 인증이 제거됩니다.

Azure Functions 애플리케이션에 Azure Key Vault에 대한 액세스를 부여해야 합니다.  
어떤 세 가지 작업을 순서대로 수행해야 합니까? 답변하려면 작업 목록에서 적절한 작업을 답변 영역으로 이동하여 올바른 순서로 배열하십시오.

![image](https://github.com/pureliture/pureliture/assets/61732056/9b8c0d9d-92f5-4b0e-af48-28eeadb9bb7e)

<details>
<summary>정답</summary>
  
**정답:**  

![image](https://github.com/pureliture/pureliture/assets/61732056/2b4c5366-eaa8-4246-a279-1196046ecd93)

1단계: Consumption 계획 유형으로 Azure Functions 앱을 만듭니다.  
서버리스를 위해 Consumption 계획을 사용하십시오.  
2단계: 애플리케이션에 대한 시스템 할당 관리 ID를 만듭니다.  
애플리케이션에 대한 시스템 할당 관리 ID를 만드십시오. Key Vault 참조는 현재 시스템 할당 관리 ID만 지원합니다. 사용자 할당 ID는 사용할 수 없습니다.  
3단계: 애플리케이션 ID에 대한 Key Vault에서 액세스 정책을 만듭니다.  
이전에 만든 애플리케이션 ID에 대한 Key Vault에서 액세스 정책을 만듭니다. 이 정책에서 "Get" 비밀 권한을 활성화하십시오. 이 설정은 관리 ID와 호환되지 않으므로 "승인된 애플리케이션" 또는 applicationId 설정을 구성하지 마십시오.  
참조: [Azure App Service Key Vault 참조](https://docs.microsoft.com/en-us/azure/app-service/app-service-key-vault-references)
</details>

**Key Terms:**
- Azure Functions
- Azure Key Vault
- Managed identity
- VNet

---

### Question 13

#### English Version
You develop a website. You plan to host the website in Azure. You expect the website to experience high traffic volumes after it is published.  
You must ensure that the website remains available and responsive while minimizing cost.  
You need to deploy the website.  
What should you do?
- A. Deploy the website to a virtual machine. Configure the virtual machine to automatically scale when the CPU load is high.
- B. Deploy the website to an App Service that uses the Shared service tier. Configure the App Service plan to automatically scale when the CPU load is high.
- C. Deploy the website to a virtual machine. Configure a Scale Set to increase the virtual machine instance count when the CPU load is high.
- D. Deploy the website to an App Service that uses the Standard service tier. Configure the App Service plan to automatically scale when the CPU load is high.

<details>
<summary>Answer</summary>
  
**Correct Answer: D**  
Windows Azure Web Sites (WAWS) offers 3 modes: Standard, Free, and Shared.  
Standard mode carries an enterprise-grade SLA (Service Level Agreement) of 99.9% monthly, even for sites with just one instance.  
Standard mode runs on dedicated instances, making it different from the other ways to buy Windows Azure Web Sites.  
Incorrect Answers:  
B: Shared and Free modes do not offer the scaling flexibility of Standard, and they have some important limits.  
Shared mode, just as the name states, also uses shared Compute resources, and also has a CPU limit. So, while neither Free nor Shared is likely to be the best choice for your production environment due to these limits.
</details>

#### Korean Version
웹사이트를 개발합니다. 웹사이트를 Azure에서 호스팅할 계획입니다. 웹사이트가 게시된 후 높은 트래픽 볼륨을 경험할 것으로 예상됩니다.  
웹사이트가 사용 가능하고 응답성을 유지하면서 비용을 최소화해야 합니다.  
웹사이트를 배포해야 합니다.  
어떻게 해야 합니까?
- A. 웹사이트를 가상 머신에 배포합니다. CPU 부하가 높을 때 가상 머신이 자동으로 확장되도록 구성합니다.
- B. 웹사이트를 공유 서비스 계층을 사용하는 App Service에 배포합니다. CPU 부하가 높을 때 App Service 계획이 자동으로 확장되도록 구성합니다.
- C. 웹사이트를 가상 머신에 배포합니다. CPU 부하가 높을 때 가상 머신 인스턴스 수를 늘리도록 Scale Set을 구성합니다.
- D. 웹사이트를 표준 서비스 계층을 사용하는 App Service에 배포합니다. CPU 부하가 높을 때 App Service 계획이 자동으로 확장되도록 구성합니다.

<details>
<summary>정답</summary>
  
**정답: D**  
Windows Azure Web Sites (WAWS)는 세 가지 모드를 제공합니다: 표준(Standard), 무료(Free), 공유(Shared).  
표준 모드는 월간 99.9%의 엔터프라이즈 등급 SLA(서비스 수준 계약)를 제공합니다, 심지어 하나의 인스턴스만 있는 사이트라도.  
표준 모드는 전용 인스턴스에서 실행되므로 다른 Windows Azure 웹 사이트 구매 방식과 다릅니다.  
오답:  
B: 공유 및 무료 모드는 표준 모드의 확장 유연성을 제공하지 않으며, 몇 가지 중요한 제한이 있습니다.  
공유 모드는 이름 그대로 공유된 컴퓨팅 리소스를 사용하며 CPU 한도도 있습니다. 따라서 이러한 제한으로 인해 생산 환경에서는 무료 또는 공유 모드를 선택하는 것이 최선이 아닙니다.
</details>

**Key Terms:**
- Azure Web Sites
- App Service
- Scaling
- Service tiers



</details>
