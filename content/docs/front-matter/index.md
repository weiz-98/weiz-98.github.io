---
title: "Front Matter"
draft: false
summary: "All the front matter variables available in Blowfish."
tags: ["front matter", "config", "docs"]
date: 2023-04-08
---

{{< button href="#button" target="_self" >}}
Call to action
{{< /button >}}

{{< github repo="nunocoracao/blowfish" >}}

In addition to the [default Hugo front matter parameters](https://gohugo.io/content-management/front-matter/#front-matter-variables), Blowfish adds a number of additional options to customise the presentation of individual articles. All the available theme front matter parameters are listed below.

```Cpp
// 时间复杂度：O(n)
// 空间复杂度：O(1)
class Solution {
public:
    int removeElement(vector<int>& nums, int val) {
        int slowIndex = 0;
        for (int fastIndex = 0; fastIndex < nums.size(); fastIndex++) {
            if (val != nums[fastIndex]) {
                nums[slowIndex++] = nums[fastIndex];
            }
        }
        return slowIndex;
    }
};
```
