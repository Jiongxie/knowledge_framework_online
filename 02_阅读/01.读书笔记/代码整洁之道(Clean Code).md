## 读书笔记：《Clean Code: A Handbook of Agile Software Craftsmanship》  - [美] Robert C·Martin


一、整洁代码  

> 1、我们为什么要写代码？
    
    `扯淡！我们永远抛不掉代码。`
    `代码呈现了需求的细节，在某些层面上，这些细节无法被忽略或抽象，必须明确之。而将需求明确到机器可以执行的细节程度，就是编程要做的事。
    而这种规约正是代码。`

> 2、写代码过程中有哪些问题   
    
    `修改无小事；每次修改都可能影响到其他两三处代码！`
    `价值谜题；需求变化背离初期设计、进度紧张以及无用的营销业务场景，背负期限压力的驱动下，只好制造混乱。`
    `华丽的新设计；`   



> 3、
  
    
        /**
         * 重置应用appSecret
         * @param appSecretRequest
         * @return
         */
        RpcResult<String> resetAppSecret(ResetAppSecretRequest appSecretRequest);
