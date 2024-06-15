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




</details>
