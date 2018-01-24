---
title: "ASP.NET Core 2.0 入门"
author: rick-anderson
description: "介绍如何使用 ASP.NET Core 创建并运行简单的 Hello World 应用的快速教程。"
ms.author: riande
manager: wpickett
ms.date: 10/18/2017
ms.topic: get-started-article
ms.technology: aspnet
ms.prod: asp.net-core
uid: getting-started
ms.openlocfilehash: b5f1fb0de2776177374b8b4d5ea6041b0fc653a9
ms.sourcegitcommit: 3e303620a125325bb9abd4b2d315c106fb8c47fd
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/19/2018
---
# <a name="get-started-with-aspnet-core"></a><span data-ttu-id="03fe9-103">ASP.NET Core 入门</span><span class="sxs-lookup"><span data-stu-id="03fe9-103">Get Started with ASP.NET Core</span></span>

> [!NOTE]
> <span data-ttu-id="03fe9-104">这些说明适用于 ASP.NET Core 的最新版本。</span><span class="sxs-lookup"><span data-stu-id="03fe9-104">These instructions are for the latest version of ASP.NET Core.</span></span> <span data-ttu-id="03fe9-105">想要从早期版本开始？</span><span class="sxs-lookup"><span data-stu-id="03fe9-105">Looking to get started with an earlier version?</span></span> <span data-ttu-id="03fe9-106">请参阅[本教程的 1.1 版本](xref:getting-started-1.1)。</span><span class="sxs-lookup"><span data-stu-id="03fe9-106">See [the 1.1 version of this tutorial](xref:getting-started-1.1).</span></span>

1. <span data-ttu-id="03fe9-107">安装 [.NET Core](https://www.microsoft.com/net/core/)。</span><span class="sxs-lookup"><span data-stu-id="03fe9-107">Install [.NET Core](https://www.microsoft.com/net/core/).</span></span>

2. <span data-ttu-id="03fe9-108">创建新的 .NET Core 项目。</span><span class="sxs-lookup"><span data-stu-id="03fe9-108">Create a new .NET Core project.</span></span>

   <span data-ttu-id="03fe9-109">在 macOS 和 Linux 上，打开终端窗口。</span><span class="sxs-lookup"><span data-stu-id="03fe9-109">On macOS and Linux, open a terminal window.</span></span> <span data-ttu-id="03fe9-110">在 Windows 上，打开命令提示符。</span><span class="sxs-lookup"><span data-stu-id="03fe9-110">On Windows, open a command prompt.</span></span> <span data-ttu-id="03fe9-111">输入以下命令：</span><span class="sxs-lookup"><span data-stu-id="03fe9-111">Enter the following command:</span></span>

    ```terminal
    dotnet new razor -o aspnetcoreapp
    ```
    
4. <span data-ttu-id="03fe9-112">运行应用。</span><span class="sxs-lookup"><span data-stu-id="03fe9-112">Run the app.</span></span>

    <span data-ttu-id="03fe9-113">使用以下命令运行应用：</span><span class="sxs-lookup"><span data-stu-id="03fe9-113">Use the following commands to run the app:</span></span>

    ```terminal
    cd aspnetcoreapp
    dotnet run
    ```

5. <span data-ttu-id="03fe9-114">浏览到 [http://localhost:5000](http://localhost:5000)</span><span class="sxs-lookup"><span data-stu-id="03fe9-114">Browse to [http://localhost:5000](http://localhost:5000)</span></span>

6. <span data-ttu-id="03fe9-115">打开 Pages/About.cshtml 并将页面修改为显示消息“Hello, world!</span><span class="sxs-lookup"><span data-stu-id="03fe9-115">Open *Pages/About.cshtml* and modify the page to display the message "Hello, world!</span></span> <span data-ttu-id="03fe9-116">The time on the server is @DateTime.Now”：</span><span class="sxs-lookup"><span data-stu-id="03fe9-116">The time on the server is @DateTime.Now ":</span></span>

    [!code-html[Main](getting-started/sample/getting-started/about.cshtml?highlight=9&range=1-9)]

7. <span data-ttu-id="03fe9-117">浏览到 [http://localhost:5000/About](http://localhost:5000/About) 并验证更改。</span><span class="sxs-lookup"><span data-stu-id="03fe9-117">Browse to [http://localhost:5000/About](http://localhost:5000/About) and verify the changes.</span></span>

### <a name="next-steps"></a><span data-ttu-id="03fe9-118">后续步骤</span><span class="sxs-lookup"><span data-stu-id="03fe9-118">Next steps</span></span>

<span data-ttu-id="03fe9-119">有关入门教程，请参阅 [ASP.NET Core 教程](tutorials/index.md)</span><span class="sxs-lookup"><span data-stu-id="03fe9-119">For getting-started tutorials, see [ASP.NET Core Tutorials](tutorials/index.md)</span></span>

<span data-ttu-id="03fe9-120">有关 ASP.NET Core 概念和体系结构的简介，请参阅 [ASP.NET Core 简介](index.md)和 [ASP.NET Core 基础知识](fundamentals/index.md)。</span><span class="sxs-lookup"><span data-stu-id="03fe9-120">For an introduction to ASP.NET Core concepts and architecture, see [ASP.NET Core Introduction](index.md) and [ASP.NET Core Fundamentals](fundamentals/index.md).</span></span>

<span data-ttu-id="03fe9-121">ASP.NET Core 应用可使用 .NET Core 或.NET Framework 基类库和运行时。</span><span class="sxs-lookup"><span data-stu-id="03fe9-121">An ASP.NET Core app can use the .NET Core or .NET Framework Base Class Library and runtime.</span></span> <span data-ttu-id="03fe9-122">有关详细信息，请参阅[在 .NET Core 和 .NET Framework 之间进行选择](https://docs.microsoft.com/dotnet/articles/standard/choosing-core-framework-server)。</span><span class="sxs-lookup"><span data-stu-id="03fe9-122">For more information, see [Choosing between .NET Core and .NET Framework](https://docs.microsoft.com/dotnet/articles/standard/choosing-core-framework-server).</span></span>