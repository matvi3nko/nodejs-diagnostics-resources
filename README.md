
# nodejs-diagnostics-resources
## Resources links from my talk "Node.js applications diagnostics under the hood"
## and useful links on this topic for studying Diagnostics.


1. llnode: https://github.com/nodejs/llnode 

2. node-report https://github.com/nodejs/node-report 

3. build D8 https://github.com/v8/v8/wiki/Building-from-Source 

4. D8 find memory leaks https://github.com/v8/v8/wiki/Memory-Leaks

5. how to handle libuv in node-report: https://developer.ibm.com/node/2017/06/09/additional-libuv-handle-information-node-report-2-2-0/
6. V8 GC: https://www.youtube.com/watch?v=DSBLAG2IvsY&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=40

7. GC parser: https://github.com/aliyun-node/v8-gc-log-parser

8. Source GC Tracer V8 must read: https://github.com/v8/v8/blob/9a5650ac9e89a9827b34b87d3204fc63a7e08e2a/src/heap/gc-tracer.cc#L385-L427

9. Managing Garbage Collection: https://strongloop.com/strongblog/node-js-performance-garbage-collection/

10. Memory leaks: https://www.youtube.com/watch?v=FocrqytWkjM&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=34

11. Objects graph topology in Memory: https://phptouch.com/category/v8/

12. Must read. Static, automatic and dynamic allocation of memory. https://stackoverflow.com/questions/8385322/difference-between-static-memory-allocation-and-dynamic-memory-allocation 

13. C++ external strings:  https://docs.google.com/presentation/d/1OqjVqRhtwlKeKfvMdX6HaCIu9wpZsrzqpIVIwQSuiXQ/edit#slide=id.g1453eb7f19_1_266

14. Real life troubleshooting in Node.js: 
https://www.youtube.com/watch?v=88OLQ_fb2Oo&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8&index=29

15. Profiling strategy: https://www.youtube.com/watch?v=MnA-IDpd6Sg

16. Mdb: https://www.joyent.com/blog/mdb-and-node-js

17. https://yunong.io/2015/11/13/debugging-node-js-in-production/

18. Debugging with mdb guide: https://www.joyent.com/blog/mdb-and-node-js

19. Debugging in prod (Netflix) with Mdb: https://www.slideshare.net/yunongx/debugging-node-in-prod

20. Debugging in prod (Netflix) video: https://www.youtube.com/watch?v=O1YP8QP9gLA

21. Memory Profiling: https://www.youtube.com/watch?time_continue=2&v=taADm6ndvVo

22. NodeReport https://developer.ibm.com/node/2016/06/28/future-directions-for-diagnostics-in-node-js-production-environments/

23. Post-Mortem Diagnostics & Debugging: https://blog.risingstack.com/post-mortem-diagnostics-debugging-node-js-at-scale/

24. Error handling: https://www.joyent.com/node-js/production/design/errors

25. Handle errors centrally: https://github.com/i0natan/nodebestpractices/blob/master/sections/errorhandling/centralizedhandling.md

26. Error handling example: https://stackoverflow.com/questions/7310521/node-js-best-practice-exception-handling

27. “Debug” module: https://www.npmjs.com/package/debug

28. How to track down CPU issues in Node.js https://www.dynatrace.com/blog/category/digital-experience/

29. How to trach down CPU issues: https://www.dynatrace.com/blog/how-to-track-down-cpu-issues-in-node-js/

30. NODE_ENV goal: https://www.dynatrace.com/blog/the-drastic-effects-of-omitting-node_env-in-your-express-js-applications/

31. Instrumentals in production. AsyncWrap and X-Transaction-Id: https://www.youtube.com/watch?v=nvHxA7dYw0w

32. Getting ready you app to prod: https://www.youtube.com/watch?v=lUsNne-_VIk

33. [Read] Making The Case For Building Scalable Stateful Services In The Modern Era: http://highscalability.com/blog/2015/10/12/making-the-case-for-building-scalable-stateful-services-in-t.html

34. AsyncWrap – AsyncHooks slides: http://lanceball.com/slides/nodevember2016/#/1

35. Decofun – names anonymous function according to their context: https://github.com/davidmarkclements/decofun

36. DEVELOP DEBUGGING TECHNIQUES: http://www.nearform.com/nodecrunch/node-js-develop-debugging-techniques/

37. Profiling with BCC on Linux: https://github.com/iovisor/bcc

38. Monitoring and profiling with N|Solid: https://vimeopro.com/nodesummit/node-summit-2016/video/180476155

39. Lazy V8 parsing. D8 and optimize.js: https://medium.com/devschacht/lazy-javascript-parsing-in-v8-99b5c3a6cbba

40. Node prod best Tips: http://goldbergyoni.com/checklist-best-practice-of-node-js-in-production/

41. How V8 runs JavaScript: https://skillsmatter.com/skillscasts/10205-how-v8-runs-javascript

42. The price of logging. 0x: https://skillsmatter.com/skillscasts/10479-the-cost-of-logging-

43. Google IO 2017, Turbofan and Ingnition: https://www.youtube.com/watch?v=EdFDJANJJLs

44. Profiling Node.js: https://www.codementor.io/nodejs/tutorial/nodejs-profiling

45. The Flame charts: http://www.brendangregg.com/flamegraphs.html

46. Node source lldb perf flame graph: https://youtu.be/t25c9LqkWNQ

47. Understanding V8’s Bytecode: https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775

48. Optimization killers: https://github.com/petkaantonov/bluebird/wiki/Optimization-killers

49. http://mrale.ph/blog/2011/12/18/v8-optimization-checklist.html

50. https://gist.github.com/trevnorris/6fea5ab2632dff8b5b25#file-perf-training-syllabus-md

51. Lldb - llnode: https://asciinema.org/a/29589

52. Post-mortem & live debugging with llnode and lldb: https://vimeo.com/172629474

53. Jbt for lldb [deprecated but interesting] https://www.youtube.com/watch?v=t25c9LqkWNQ&feature=youtu.be

54. Advances in core-dump debugging for Node.js: https://developer.ibm.com/node/2016/09/27/advances-in-core-dump-debugging-for-node-js/

55. Exploring Node.js core dumps using the llnode plugin for lldb: https://developer.ibm.com/node/2016/08/15/exploring-node-js-core-dumps-using-the-llnode-plugin-for-lldb/

56. App performance: https://github.com/vhf/v8-bailout-reasons#inlining-bailed-out

57. Dtrace: https://github.com/joyent/node-stackvis

58. Node.js community benchmarking with Michael Dawson: https://www.youtube.com/watch?v=YZ9fipNSfsA&index=60&list=PLfMzBWSH11xYaaHMalNKqcEurBH8LstB8

59. Uv_fs_read: http://docs.libuv.org/en/v1.x/fs.html

74. Диагностика на JAVA 2 часа доклад (тоже полезно!) https://www.youtube.com/watch?v=0pyZERLBZvQ

