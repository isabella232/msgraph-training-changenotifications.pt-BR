# <a name="microsoft-graph-training-module---using-change-notifications-and-track-changes-with-microsoft-graph"></a><span data-ttu-id="4ce72-101">Módulo de treinamento do Microsoft Graph-usando notificações de alteração e controlando alterações com o Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="4ce72-101">Microsoft Graph Training Module - Using Change Notifications and Track Changes with Microsoft Graph</span></span>

<span data-ttu-id="4ce72-102">Este módulo mostrará a você como trabalhar com as notificações de alteração (WebHooks) & controlar alterações (consulta Delta) no Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="4ce72-102">This module will introduce you to working with change notifications (webhooks) & track changes (delta query) in the Microsoft Graph.</span></span>

## <a name="lab---change-notifications-and-track-changes-with-the-microsoft-graph"></a><span data-ttu-id="4ce72-103">Laboratório-alterar notificações e controlar alterações com o Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="4ce72-103">Lab - Change Notifications and Track Changes with the Microsoft Graph</span></span>

<span data-ttu-id="4ce72-104">Neste laboratório, você criará um aplicativo de console do .NET Core que recebe notificações de alteração do Microsoft Graph quando uma atualização é feita para uma conta de usuário no Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="4ce72-104">In this lab you will create a .NET Core console application that receives change notifications from the Microsoft Graph when an update is made to a users account in Azure Active Directory (Azure AD).</span></span> <span data-ttu-id="4ce72-105">O aplicativo gerenciará a assinatura de notificação de alteração e usará o controle de alterações no Microsoft Graph para garantir que nenhuma alteração seja perdida.</span><span class="sxs-lookup"><span data-stu-id="4ce72-105">The application will managed the Change Notification subscription and use Track Changes in the Microsoft Graph to ensure no changes are missed.</span></span>

- [<span data-ttu-id="4ce72-106">Manual do laboratório</span><span class="sxs-lookup"><span data-stu-id="4ce72-106">Lab Manual</span></span>](./Lab.md)

## <a name="demos"></a><span data-ttu-id="4ce72-107">Demonstrações</span><span class="sxs-lookup"><span data-stu-id="4ce72-107">Demos</span></span>

- [<span data-ttu-id="4ce72-108">Criar um aplicativo do .NET Core</span><span class="sxs-lookup"><span data-stu-id="4ce72-108">Create a .NET Core app</span></span>](./demos/01-create-application)
- [<span data-ttu-id="4ce72-109">Adicionar ciclo de vida de assinatura</span><span class="sxs-lookup"><span data-stu-id="4ce72-109">Add Subscription Lifecycle</span></span>](./demos/02-subscription-management)
- [<span data-ttu-id="4ce72-110">Adicionar alterações de controle</span><span class="sxs-lookup"><span data-stu-id="4ce72-110">Add Track Changes</span></span>](./demos/03-track-changes)

## <a name="watch-the-module"></a><span data-ttu-id="4ce72-111">Assista ao módulo</span><span class="sxs-lookup"><span data-stu-id="4ce72-111">Watch the module</span></span>

<span data-ttu-id="4ce72-112">Este módulo foi gravado e está disponível no canal do Office Development YouTube: [alterar notificações e controlar alterações com o Microsoft Graph](https://youtu.be/fThiCZmIcMQ)</span><span class="sxs-lookup"><span data-stu-id="4ce72-112">This module has been recorded and is available in the Office Development YouTube channel: [Change Notifications and Track Changes with the Microsoft Graph](https://youtu.be/fThiCZmIcMQ)</span></span>

## <a name="contributors"></a><span data-ttu-id="4ce72-113">Colaboradores</span><span class="sxs-lookup"><span data-stu-id="4ce72-113">Contributors</span></span>

|        <span data-ttu-id="4ce72-114">Funções</span><span class="sxs-lookup"><span data-stu-id="4ce72-114">Roles</span></span>         |                                       <span data-ttu-id="4ce72-115">Autor (es)</span><span class="sxs-lookup"><span data-stu-id="4ce72-115">Author(s)</span></span>                                       |
| -------------------- | ------------------------------------------------------------------------------------- |
| <span data-ttu-id="4ce72-116">Manuais/slides do laboratório</span><span class="sxs-lookup"><span data-stu-id="4ce72-116">Lab Manuals / Slides</span></span> | <span data-ttu-id="4ce72-117">Andrew Connell (Microsoft MVP, Voitanos) [@andrewconnell](//github.com/andrewconnell)</span><span class="sxs-lookup"><span data-stu-id="4ce72-117">Andrew Connell (Microsoft MVP, Voitanos) [@andrewconnell](//github.com/andrewconnell)</span></span> |
| <span data-ttu-id="4ce72-118">Patrocinador/suporte</span><span class="sxs-lookup"><span data-stu-id="4ce72-118">Sponsor / Support</span></span>    | <span data-ttu-id="4ce72-119">Jeremy Thake (Microsoft) [@jthake](//github.com/jthake)</span><span class="sxs-lookup"><span data-stu-id="4ce72-119">Jeremy Thake (Microsoft) [@jthake](//github.com/jthake)</span></span>                               |

## <a name="version-history"></a><span data-ttu-id="4ce72-120">Histórico de versão</span><span class="sxs-lookup"><span data-stu-id="4ce72-120">Version history</span></span>

| <span data-ttu-id="4ce72-121">Versão</span><span class="sxs-lookup"><span data-stu-id="4ce72-121">Version</span></span> |      <span data-ttu-id="4ce72-122">Data</span><span class="sxs-lookup"><span data-stu-id="4ce72-122">Date</span></span>      |                     <span data-ttu-id="4ce72-123">Comments</span><span class="sxs-lookup"><span data-stu-id="4ce72-123">Comments</span></span>                     |
| ------- | -------------- | ------------------------------------------------ |
| <span data-ttu-id="4ce72-124">1.3</span><span class="sxs-lookup"><span data-stu-id="4ce72-124">1.3</span></span>     | <span data-ttu-id="4ce72-125">18 de junho de 2019</span><span class="sxs-lookup"><span data-stu-id="4ce72-125">June 18, 2019</span></span>  | <span data-ttu-id="4ce72-126">Leiame atualizado para a gravação de screencast atualizada</span><span class="sxs-lookup"><span data-stu-id="4ce72-126">Updated readme to refreshed screencast recording</span></span> |
| <span data-ttu-id="4ce72-127">1.2</span><span class="sxs-lookup"><span data-stu-id="4ce72-127">1.2</span></span>     | <span data-ttu-id="4ce72-128">30 de maio de 2019</span><span class="sxs-lookup"><span data-stu-id="4ce72-128">May 30, 2019</span></span>   | <span data-ttu-id="4ce72-129">Atualização de conteúdo do Fy2019Q4</span><span class="sxs-lookup"><span data-stu-id="4ce72-129">Fy2019Q4 content refresh</span></span>                         |
| <span data-ttu-id="4ce72-130">1.1</span><span class="sxs-lookup"><span data-stu-id="4ce72-130">1.1</span></span>     | <span data-ttu-id="4ce72-131">9 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="4ce72-131">April 9, 2019</span></span>  | <span data-ttu-id="4ce72-132">Adicionado link do screencast</span><span class="sxs-lookup"><span data-stu-id="4ce72-132">Added screencast link</span></span>                            |
| <span data-ttu-id="4ce72-133">1.0</span><span class="sxs-lookup"><span data-stu-id="4ce72-133">1.0</span></span>     | <span data-ttu-id="4ce72-134">14 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="4ce72-134">March 14, 2019</span></span> | <span data-ttu-id="4ce72-135">Novo módulo enviado</span><span class="sxs-lookup"><span data-stu-id="4ce72-135">New module submitted</span></span>                             |

## <a name="disclaimer"></a><span data-ttu-id="4ce72-136">Aviso de isenção de responsabilidade</span><span class="sxs-lookup"><span data-stu-id="4ce72-136">Disclaimer</span></span>

<span data-ttu-id="4ce72-137">**Este código é fornecido _como está_ sem garantia de qualquer tipo, seja expressa ou implícita, incluindo quaisquer garantias implícitas de ADEQÜAÇÃO para um propósito específico, comercialização ou não-violação.**</span><span class="sxs-lookup"><span data-stu-id="4ce72-137">**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**</span></span>

<img src="https://telemetry.sharepointpnp.com/msgraph-training-changenotifications" />
