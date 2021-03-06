# 查询Application属性<a name="smn_api_57005"></a>

## 功能介绍<a name="zh-cn_topic_0118694339_section19819501"></a>

-   接口名称

    GetApplicationAttributes

-   功能描述

    获取应用平台属性。


## URI<a name="zh-cn_topic_0118694339_section44157788"></a>

-   URI格式

    GET /v2/\{project\_id\}/notifications/applications/\{application\_urn\}

-   参数说明

    <a name="zh-cn_topic_0118694339_table33304091"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0118694339_row53503647"><th class="cellrowborder" valign="top" width="20.990000000000002%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0118694339_p38828151"><a name="zh-cn_topic_0118694339_p38828151"></a><a name="zh-cn_topic_0118694339_p38828151"></a>名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="19.75%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0118694339_p58072540"><a name="zh-cn_topic_0118694339_p58072540"></a><a name="zh-cn_topic_0118694339_p58072540"></a>是否必选</p>
    </th>
    <th class="cellrowborder" valign="top" width="20.990000000000002%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0118694339_p6255285"><a name="zh-cn_topic_0118694339_p6255285"></a><a name="zh-cn_topic_0118694339_p6255285"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="38.269999999999996%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0118694339_p36916075"><a name="zh-cn_topic_0118694339_p36916075"></a><a name="zh-cn_topic_0118694339_p36916075"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0118694339_row10478731"><td class="cellrowborder" valign="top" width="20.990000000000002%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0118694339_p43470919"><a name="zh-cn_topic_0118694339_p43470919"></a><a name="zh-cn_topic_0118694339_p43470919"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.75%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0118694339_p31483518"><a name="zh-cn_topic_0118694339_p31483518"></a><a name="zh-cn_topic_0118694339_p31483518"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="20.990000000000002%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0118694339_p28186"><a name="zh-cn_topic_0118694339_p28186"></a><a name="zh-cn_topic_0118694339_p28186"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="38.269999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0118694339_p2283139"><a name="zh-cn_topic_0118694339_p2283139"></a><a name="zh-cn_topic_0118694339_p2283139"></a>项目ID</p>
    <p id="zh-cn_topic_0118694339_p20548256"><a name="zh-cn_topic_0118694339_p20548256"></a><a name="zh-cn_topic_0118694339_p20548256"></a>获取项目ID请参考<a href="获取项目ID.md">获取项目ID</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0118694339_row62509229"><td class="cellrowborder" valign="top" width="20.990000000000002%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0118694339_p30082780"><a name="zh-cn_topic_0118694339_p30082780"></a><a name="zh-cn_topic_0118694339_p30082780"></a>application_urn</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.75%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0118694339_p20786140"><a name="zh-cn_topic_0118694339_p20786140"></a><a name="zh-cn_topic_0118694339_p20786140"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="20.990000000000002%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0118694339_p5955797"><a name="zh-cn_topic_0118694339_p5955797"></a><a name="zh-cn_topic_0118694339_p5955797"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="38.269999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0118694339_p12657518"><a name="zh-cn_topic_0118694339_p12657518"></a><a name="zh-cn_topic_0118694339_p12657518"></a>Application的唯一资源标识，可通过<a href="查询Application.md">查询Application</a>获取该标识。</p>
    </td>
    </tr>
    </tbody>
    </table>


## 请求消息<a name="zh-cn_topic_0118694339_section61875774"></a>

-   请求样例

    ```
    GET https://{SMN_Endpoint}/v2/{project_id}/notifications/applications/{application_urn}
    ```


## 响应消息<a name="zh-cn_topic_0118694339_section20011062"></a>

-   要素说明

    <a name="zh-cn_topic_0118694339_table65541146"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0118694339_row64426188"><th class="cellrowborder" valign="top" width="29.872987298729875%" id="mcps1.1.4.1.1"><p id="zh-cn_topic_0118694339_p51138754"><a name="zh-cn_topic_0118694339_p51138754"></a><a name="zh-cn_topic_0118694339_p51138754"></a>名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="35.063506350635066%" id="mcps1.1.4.1.2"><p id="zh-cn_topic_0118694339_p48598416"><a name="zh-cn_topic_0118694339_p48598416"></a><a name="zh-cn_topic_0118694339_p48598416"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="35.063506350635066%" id="mcps1.1.4.1.3"><p id="zh-cn_topic_0118694339_p44157663"><a name="zh-cn_topic_0118694339_p44157663"></a><a name="zh-cn_topic_0118694339_p44157663"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0118694339_row9466911"><td class="cellrowborder" valign="top" width="29.872987298729875%" headers="mcps1.1.4.1.1 "><p id="zh-cn_topic_0118694339_p28622303"><a name="zh-cn_topic_0118694339_p28622303"></a><a name="zh-cn_topic_0118694339_p28622303"></a>request_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.2 "><p id="zh-cn_topic_0118694339_p36705216"><a name="zh-cn_topic_0118694339_p36705216"></a><a name="zh-cn_topic_0118694339_p36705216"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.3 "><p id="zh-cn_topic_0118694339_p20332521"><a name="zh-cn_topic_0118694339_p20332521"></a><a name="zh-cn_topic_0118694339_p20332521"></a>请求的唯一标识ID。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0118694339_row58458402"><td class="cellrowborder" valign="top" width="29.872987298729875%" headers="mcps1.1.4.1.1 "><p id="zh-cn_topic_0118694339_p37510120"><a name="zh-cn_topic_0118694339_p37510120"></a><a name="zh-cn_topic_0118694339_p37510120"></a>attributes</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.2 "><p id="zh-cn_topic_0118694339_p18420850"><a name="zh-cn_topic_0118694339_p18420850"></a><a name="zh-cn_topic_0118694339_p18420850"></a>Application_attributes结构体</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.3 "><p id="zh-cn_topic_0118694339_p15693864"><a name="zh-cn_topic_0118694339_p15693864"></a><a name="zh-cn_topic_0118694339_p15693864"></a>请参见<a href="#table1480745216468">表1</a>。</p>
    </td>
    </tr>
    <tr id="row1348515372063"><td class="cellrowborder" valign="top" width="29.872987298729875%" headers="mcps1.1.4.1.1 "><p id="p248515379613"><a name="p248515379613"></a><a name="p248515379613"></a>application_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.2 "><p id="p0485113713614"><a name="p0485113713614"></a><a name="p0485113713614"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="35.063506350635066%" headers="mcps1.1.4.1.3 "><p id="p1148517371764"><a name="p1148517371764"></a><a name="p1148517371764"></a>Application的唯一标识ID。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 1**  Application\_attributes结构体

    <a name="table1480745216468"></a>
    <table><thead align="left"><tr id="row20839185244616"><th class="cellrowborder" valign="top" width="34.65346534653465%" id="mcps1.2.4.1.1"><p id="p19839352124611"><a name="p19839352124611"></a><a name="p19839352124611"></a>名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="21.782178217821784%" id="mcps1.2.4.1.2"><p id="p383965219468"><a name="p383965219468"></a><a name="p383965219468"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="43.56435643564357%" id="mcps1.2.4.1.3"><p id="p138399524465"><a name="p138399524465"></a><a name="p138399524465"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2839125294619"><td class="cellrowborder" valign="top" width="34.65346534653465%" headers="mcps1.2.4.1.1 "><p id="p13839145218464"><a name="p13839145218464"></a><a name="p13839145218464"></a>enabled</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.782178217821784%" headers="mcps1.2.4.1.2 "><p id="p18839105220462"><a name="p18839105220462"></a><a name="p18839105220462"></a>boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.56435643564357%" headers="mcps1.2.4.1.3 "><p id="p1839952134616"><a name="p1839952134616"></a><a name="p1839952134616"></a>应用平台是否启用</p>
    </td>
    </tr>
    <tr id="row15839185204612"><td class="cellrowborder" valign="top" width="34.65346534653465%" headers="mcps1.2.4.1.1 "><p id="p4839175274617"><a name="p4839175274617"></a><a name="p4839175274617"></a>apple_certificate_expiration_date</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.782178217821784%" headers="mcps1.2.4.1.2 "><p id="p19839125218462"><a name="p19839125218462"></a><a name="p19839125218462"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.56435643564357%" headers="mcps1.2.4.1.3 "><p id="p1839205234610"><a name="p1839205234610"></a><a name="p1839205234610"></a>苹果证书过期时间</p>
    <p id="p776310367391"><a name="p776310367391"></a><a name="p776310367391"></a>APNS、APNS_SANDBOX平台特有属性</p>
    <p id="p889025912288"><a name="p889025912288"></a><a name="p889025912288"></a>时间格式为UTC时间，YYYY-MM-DDTHH:MM:SSZ</p>
    </td>
    </tr>
    </tbody>
    </table>


-   响应样例

    ```
    {
        "request_id": "c2b8643dc12b5e77ad6e35a16003229b", 
        "application_id": "b1b8643dc12b4g77ad6e35a16003119b",
        "attributes": {
            "enabled": "true", 
            "apple_certificate_expiration_date": "2018-03-09T12:21:40Z"
        }
    }
    ```


## 返回值<a name="section242171292113"></a>

请参考[返回值](返回值.md)。

## 错误码<a name="section73211020122511"></a>

请参考[错误码说明](错误码说明.md)。

