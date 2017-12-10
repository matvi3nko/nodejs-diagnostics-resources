
# nodejs-diagnostics-resources
Resources links from my talk "Node.js applications diagnostics under the hood"


1. llnode https://github.com/nodejs/llnode 
2. node-report https://github.com/nodejs/node-report 
3. build D8 https://github.com/v8/v8/wiki/Building-from-Source 
4. D8 find memory leaks https://github.com/v8/v8/wiki/Memory-Leaks
5. how to handle libuv in node-report https://developer.ibm.com/node/2017/06/09/additional-libuv-handle-information-node-report-2-2-0/
6. V8 GC
https://www.youtube.com/watch?v=DSBLAG2IvsY&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=40

7. parser: https://github.com/aliyun-node/v8-gc-log-parser

8. Source GC Tracer V8 must read https://github.com/v8/v8/blob/9a5650ac9e89a9827b34b87d3204fc63a7e08e2a/src/heap/gc-tracer.cc#L385-L427

9. https://strongloop.com/strongblog/node-js-performance-garbage-collection/

10. https://www.youtube.com/watch?v=FocrqytWkjM&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=34 Memory leaks

11. https://phptouch.com/category/v8/ Оч круто

12. https://stackoverflow.com/questions/8385322/difference-between-static-memory-allocation-and-dynamic-memory-allocation Статическое, автоматическое и динамическое выделение памяти.

13. C++ external strings https://docs.google.com/presentation/d/1OqjVqRhtwlKeKfvMdX6HaCIu9wpZsrzqpIVIwQSuiXQ/edit#slide=id.g1453eb7f19_1_266

14. Real life troubleshooting in Node.js
https://www.youtube.com/watch?v=88OLQ_fb2Oo&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=29

15. https://www.youtube.com/watch?v=MnA-IDpd6Sg

16. Mdb https://www.joyent.com/blog/mdb-and-node-js

17. https://yunong.io/2015/11/13/debugging-node-js-in-production/

18. https://www.joyent.com/blog/mdb-and-node-js Почему mdb

19. Debugging in prod (Netflix) with Mdb https://www.slideshare.net/yunongx/debugging-node-in-prod

20. https://www.youtube.com/watch?v=O1YP8QP9gLA

21. https://www.youtube.com/watch?v=CiqzuIUwHl8

22. https://www.slideshare.net/yunongx/node-interactive-debugging-nodejs-in-production

23. Memory leaks https://www.youtube.com/watch?time_continue=2&v=taADm6ndvVo

24. NodeReport https://developer.ibm.com/node/2016/06/28/future-directions-for-diagnostics-in-node-js-production-environments/

25. https://blog.risingstack.com/post-mortem-diagnostics-debugging-node-js-at-scale/

26. Error handling https://www.joyent.com/node-js/production/design/errors

27. https://stackoverflow.com/questions/7310521/node-js-best-practice-exception-handling

28.TO READ https://medium.com/the-node-js-collection/why-the-hell-would-you-use-node-js-4b053b94ab8e

29. “Debug” module https://www.npmjs.com/package/debug

30. How to track down CPU issues in Node.js https://www.dynatrace.com/blog/category/digital-experience/

31. https://www.dynatrace.com/blog/how-to-track-down-cpu-issues-in-node-js/

32. https://www.dynatrace.com/blog/the-drastic-effects-of-omitting-node_env-in-your-express-js-applications/

33. Instrumentals in production. AsyncWrap and X-Transaction-Id

34. https://www.youtube.com/watch?v=nvHxA7dYw0w

35. https://www.youtube.com/watch?v=Foaeu2F9nVk

36. Getting ready you app to prod. Meet.js. Cool!

37. https://www.youtube.com/watch?v=lUsNne-_VIk

38. http://highscalability.com/blog/2015/10/12/making-the-case-for-building-scalable-stateful-services-in-t.html

39. AsyncWrap – AsyncHooks https://archive.org/details/nodevember16-Tracing_Asynchronous_Operations_with_Nodes_AsyncWrap_API

40. http://lanceball.com/slides/nodevember2016/#/1

41. https://vimeo.com/157651344

42. Decofun – names anonymous function according to their context

43. http://www.nearform.com/nodecrunch/node-js-develop-debugging-techniques/

44. https://github.com/davidmarkclements/decofun

45. Summitjs node performance

46. https://vimeopro.com/nodesummit/node-summit-2016/video/180476155

47. Lazy V8 parsing. D8 and optimize.js

48. https://medium.com/devschacht/lazy-javascript-parsing-in-v8-99b5c3a6cbba

49. Node prod best Tips

50. http://goldbergyoni.com/checklist-best-practice-of-node-js-in-production/

51. How V8 runs JavaScript https://skillsmatter.com/skillscasts/10205-how-v8-runs-javascript

52. The price of logging. 0x nmp.

53. https://skillsmatter.com/skillscasts/10479-the-cost-of-logging-

54. Google IO 2017 https://www.youtube.com/watch?v=EdFDJANJJLs

55. https://www.codementor.io/nodejs/tutorial/nodejs-profiling

56. The Flame charts http://www.brendangregg.com/flamegraphs.html

57. Node source lldb perf flame graph https://youtu.be/t25c9LqkWNQ

58. Understanding V8’s Bytecode https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775

59. Optimization killers https://github.com/petkaantonov/bluebird/wiki/Optimization-killers

60. http://mrale.ph/blog/2011/12/18/v8-optimization-checklist.html

61. https://gist.github.com/trevnorris/6fea5ab2632dff8b5b25#file-perf-training-syllabus-md

62. Lldb - llnode https://asciinema.org/a/29589

63. https://vimeo.com/172629474

64. https://www.youtube.com/watch?v=t25c9LqkWNQ&feature=youtu.be

65. https://www.npmjs.com/package/llnode

66. https://developer.ibm.com/node/2016/09/27/advances-in-core-dump-debugging-for-node-js/

67. https://github.com/thlorenz/lldb-jbt/blob/master/README.md

68.https://developer.ibm.com/node/2016/08/15/exploring-node-js-core-dumps-using-the-llnode-plugin-for-lldb/

69. Need to Node: Best Practices for Modern Node.js Architectures https://vimeo.com/156763689

70. App performance https://github.com/vhf/v8-bailout-reasons#inlining-bailed-out

71. Dtrace https://github.com/joyent/node-stackvis

72 Node.js community benchmarking with Michael Dawson https://www.youtube.com/watch?v=YZ9fipNSfsA&index=60&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8

73. Uv_fs_read http://docs.libuv.org/en/v1.x/fs.html

74. Диагностика на JAVA 2 часа доклад (тоже полезно!) https://www.youtube.com/watch?v=0pyZERLBZvQ

