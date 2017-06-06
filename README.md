# someTips<br/>
log4j日志级别<br/>
Date:   2017年6月6日 下午4:47:22 <br/>
author CGH <br/>
version 1.0.0<br/>
Copyright (c) 2017, 1217042356@qq.com All Rights Reserved.<br/><br/><br/><br/>



日志输出的级别，主要有以下几种：<br/><br/>
   1）ALL    打印各级日志信息包括自定义级别。<br/>
   2）TRACE    最详细的信息。一般这些信息只记录到日志文件中。自版本1.2.12[3]。<br/>
   3）DEBUG    流经系统的详细信息。一般这些信息只记录到日志文件中。<br/>
   4）INFO    令人感兴趣的运行时事件（启动/关闭）。一般这些信息将立即呈现在状态控制台上，因而要保守使用，并保持到最低限度。<br/>
   5）WARN    使用已过时的API，API的滥用，潜在错误，其他不良的或意外的运行时的状况（但不一定是错误的）。一般这些信息将立即呈现在状态控制台上。<br/>
   6）ERROR    其他运行时错误或意外情况。一般这些信息将立即呈现在状态控制台上。<br/>
   7）FATAL    导致应用程序提前终止的严重错误。一般这些信息将立即呈现在状态控制台上。<br/>
   8）OFF    最高级别，用于关闭日志记录。<br/><br/>
   
  日志的级别之间的大小关系如右所示：ALL < TRACE < DEBUG < INFO < WARN < ERROR < FATAL < OFF<br/><br/>
  
  Log4j建议只使用四个级别，优先级从高到低分别是 ERROR > WARN > INFO > DEBUG。<br/>
