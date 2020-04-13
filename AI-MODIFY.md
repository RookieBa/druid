# DRUID 修改记录
> 为适应亚信科技上海DevOps平台脚本校验功能做了一些修改
> 基于druid-1.1.17版本做了一些优化与功能新增

* ####1.1.17_7  
    1.修复owner限制遇到comment column语句会时判断不正确的问题
    
* ####1.1.17_6  
    1.解决Oracle脚本中SQLInSubQueryExpr的toString方法抛异常问题

* ####1.1.17_5  
    1.增加脚本限制owner的支持，当脚本中owner不符合要求时会抛出异常 

* ####1.1.17_1  
    1.解决Oracle解析器set命令报错问题