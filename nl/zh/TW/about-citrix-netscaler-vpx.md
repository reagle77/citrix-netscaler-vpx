---
copyright:
  years: 1994, 2017
  
lastupdated: "2017-11-02"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 關於 Citrix NetScaler VPX

Citrix NetScaler VPX 是專用虛擬軟體應用裝置，可同時在公用及專用 IBM Cloud 網路上提供負載平衡。 

## 特性

* 唯一可同時在公用及專用網路上對資料流量進行負載平衡的產品
* 使用 GUI（圖形使用者介面）或 CLI（指令行介面）進行管理
* 許多不同類型的資料流量配送，包括：
  * 循環式
  * 最少連線
  * 最少回應
  * URL 雜湊
  * 網域雜湊
  * 目的地 IP 雜湊
  * 來源 IP 雜湊
  * 最小頻寬
* SSL 加速/SSL 卸載
* GSLB（廣域伺服器負載平衡）
  * 使用 DNS 基礎架構，將用戶端連接至最佳資料中心
  * 監視資料中心的負載及可用性，以選取最佳連線選擇
* 內容切換
* 快取重新導向
* 應用程式防火牆功能
* 應用程式安全特性
* 在專用硬體上執行的虛擬應用裝置
* 可像任何其他 {{site.data.keyword.BluSoftlayer_notm}} 伺服器一樣地部署，但更考慮到彈性及可用性
* 於下列頻寬層中提供：10Mbps、200Mbps 及 1000Mbps

Citrix NetScaler VPX 可以依需求（最少 15 分鐘）在全球任何 {{site.data.keyword.BluSoftlayer_notm}} 資料中心進行部署。有數個包括您需要的速度及特性的授權模型，並提供現今雲端解決方案所需的彈性。此彈性確保每種使用案例（從小型到中型實作，一直到更大型的企業）的良好適合度。

{{site.data.keyword.BluSoftlayer_notm}} 提供含有完整、無限制 root 存取權的 NetScaler VPX 虛擬應用裝置。   

## 應用程式安全

若要保護應用程式資料流量的安全，客戶可以充分運用「應用程式內容過濾」、「存取閘道」及「Web 應用程式防火牆」這類安全特性。

## 資料流量過濾

Citrix Netscaler VPX 會過濾一般使用者對伺服器的要求，以及伺服器對一般使用者的回應。「學習」特性容許即時側寫階段作業，以及判定是否容許資料流量。


## PCI-DSS 報告

「支付卡產業 (PCI) 資料安全標準」包含處理線上信用卡付款的企業必須符合的十二個準則。PCI-DSS 報告包含那些與「應用程式防火牆」配置相關的準則清單。該報告也會列出現行配置是否符合每一個準則，並建議如何配置應用程式防火牆以符合這些標準。

## 廣域負載平衡 (GSLB)

NetScaler Platinum Edition 會將負載平衡器延伸到超過使用「廣域負載平衡」功能之資料中心的本端界限。 

## 延伸資料中心

NetScaler Platinum Edition 可讓您使用 NetScaler CloudBridge 特性，此特性提供簡單的方式，使用精靈驅動的功能表來將您的資料中心延伸至 {{site.data.keyword.BluSoftlayer_notm}}。 
