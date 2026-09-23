# Listing Doctor 隐私政策

生效日期：2026-09-23 ｜ 适用于 Chrome 扩展 **Listing Doctor — 跨境电商 Listing 诊断工具**

---

## Summary (English)

Listing Doctor runs entirely inside your browser. It reads the Amazon product page you have
open and computes its diagnosis locally on your device. **Nothing is uploaded**: no listing
text, no review text, no competitor data, no personal information and no usage analytics ever
leave your device. The extension requests no network access other than loading amazon.com pages
themselves. Locally it stores only what you create (competitor basket, listing snapshots,
preferences) plus anonymous numeric usage counters that contain no product content and no
identifiers. Uninstalling the extension deletes all of it. Contact: **eagertofly@gmail.com**

---

## 一、一句话概括

Listing Doctor 在您的浏览器本地完成全部分析，**不收集、不上传、不共享**您的任何数据。

## 二、我们处理哪些信息

1. 您当前浏览的亚马逊商品页内容（标题、五点描述、类目、品牌、评论区文字、亚马逊生成的评论摘要）。
   这些内容仅在您的浏览器内被读取和计算，用于生成本地报告。
2. 您在扩展里保存的内容：竞品篮子（商品标题、卖点、类目、品牌、评论文字、评论摘要）、
   历史快照、以及偏好设置。
3. 匿名的本地使用计数：例如"分析商品页用过几次""哪一类检查最常触发"。这些记录只包含
   数字和类别名，不包含商品标题、文案、评论原文、网址，也不包含任何能够识别您身份的信息。

## 三、这些信息存在哪里

全部保存在您浏览器本地的扩展存储（`chrome.storage.local`）中。它不会离开您的设备，
我们（扩展开发者）无法看到，也没有任何服务器接收它们。

## 四、我们不做什么

- 不把任何数据发送到互联网（本扩展不请求除 amazon.com 页面本身之外的网络访问）
- 不做用户画像、不投放广告、不出售或共享数据给第三方
- 不收集姓名、邮箱、账号、位置、通讯录等个人信息
- 不使用任何第三方分析或统计服务

## 五、权限用途（逐条说明）

- `storage`：把竞品篮子、历史与偏好保存在本地
- `activeTab`：当您点击扩展图标时，读取当前标签页以生成报告
- `scripting`：在您打开的亚马逊商品页上显示诊断卡片
- 访问 `*.amazon.com`：本扩展仅对亚马逊商品页与评论页生效，其他网站不会被读取

## 六、数据保留与删除

- 竞品篮子与历史记录：可在扩展弹窗中一键清空
- 匿名使用计数：随扩展一并删除
- 卸载扩展会删除上述全部本地数据

## 七、Limited Use（有限使用）承诺

本扩展对数据的处理严格限于其唯一用途 —— 在本地诊断亚马逊商品页的 Listing 文案质量。
我们不会将数据用于个性化广告、信用评估、借贷或其他与上述用途无关的目的。

## 八、儿童

本扩展面向电商卖家，不面向 13 岁以下儿童，也不会有意收集儿童信息。

## 九、政策变更

若本政策发生实质性变更，我们会在扩展的更新说明中告知，并更新上方的生效日期。

## 十、联系方式

如有任何隐私相关问题，请联系：**eagertofly@gmail.com**
