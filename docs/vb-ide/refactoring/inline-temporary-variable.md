---
title: "Inline temporary variable - Refactoring (Visual Basic) | Microsoft Docs"
ms.custom: ""
ms.date: "11/17/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: a63d6407-5acb-4d5f-8c0e-ecedddc07177
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
ms.workload: 
  - "multiple"
---

# Inline a temporary variable in Visual Basic
**What:** Lets you remove the use of a temporary variable and replace it with the actual code instead.

**When:** The use of the temporary variable makes the code harder to understand.  

**Why:** Removing a temporary variable may make the code easier to read in certain situations

**How:**

1. Highlight or place the text cursor inside the temporary variable to be inlined:

   ![Highlighted code](media/inline_highlight.png)

1. Next, do one of the following:
   * **Keyboard**
     * Press **Ctrl+.** to trigger the **Quick Actions and Refactorings** menu and select **Inline temporary variable** from the Preview window popup.
   * **Mouse**
     * Right-click the code, select the **Quick Actions and Refactorings** menu and select **Inline temporary variable** from the Preview window popup.

   The variable will be removed and its usages replaced by the value of the variable immediately.

   ![Inline result](media/inline_result.png)

## See Also
[Refactoring (Visual Basic)](../refactoring-vb.md)