file
diff --git a/business-behavior-monitor/docs/front/mock/mock02.json b/business-behavior-monitor/docs/front/js/mock02.json
new file mode 100644
index 0000000..5b6f927
--- /dev/null
+++ b/business-behavior-monitor/docs/front/js/mock02.json
@@ -0,0 +1,11 @@
+{
+  "class": "go.GraphLinksModel",
+  "modelData": {
+    "position": "-5 -5"
+  },
+  "nodeDataArray": [
+    {"key":"1", "text":"开始", "figure":"Circle", "fill":"#4fba4f", "stepType":1, "loc":"90 110"},
+    {"key":"2", "text":"结束", "figure":"Circle", "fill":"#CE0620", "stepType":4, "loc":"770 110"},
+    {"key":"3", "text":"填写请假信息 ",  "loc":"210 110", "remark":""},
+    {"key":"4", "text":"部门经理审核 ",  "loc":"370 110", "remark":""},
+    {"key":"5", "text":"人事审核  ",  "loc":"640 110", "remark":""},
+    {"key":"6", "text":"副总经理审核  ",  "loc":"510 40", "remark":""},
+    {"key":"7", "text":"总经理审核  ",  "loc":"500 180", "remark":""}
+  ],
+  "linkDataArray": [
+    {"from":"1", "to":"3"},
+    {"from":"3", "to":"4"},
+    {"from":"4", "to":"5"},
+    {"from":"5", "to":"2"},
+    {"from":"4", "to":"6", "key":"1001", "text":"小于5天 ", "remark":"", "condition":"Days<5"},
+    {"from":"6", "to":"5"},
+    {"from":"4", "to":"7", "key":"1002", "text":"大于5天 ", "remark":"", "condition":"Days>5"},
+    {"from":"7", "to":"5"}
+  ]}
\ No newline at end of file
diff --git a/business-behavior-monitor/docs/front/mock/mock03.json b/business-behavior-monitor/docs/front/js/mock03.json
new file mode 100644
index 0000000..d4e5e9a
--- /dev/null
+++ b/business-behavior-monitor/docs/front/js/mock03.json
@@ -0,0 +1,11 @@
+{
+  "class": "go.GraphLinksModel",
+  "modelData": {
+    "position": "-5 -5"
+  },
+  "nodeDataArray": [
+    {"key":"1", "text":"开始", "figure":"Circle", "fill":"#4fba4f", "stepType":1, "loc":"90 110"},
+    {"key":"2", "text":"结束", "figure":"Circle", "fill":"#CE0620", "stepType":4, "loc":"770 110"},
+    {"key":"3", "text":"填写请假信息 ",  "loc":"210 110", "remark":""},
+    {"key":"4", "text":"部门经理审核 ",  "loc":"370 110", "remark":""},
+    {"key":"5", "text":"人事审核  ",  "loc":"640 110", "remark":""},
+    {"key":"6", "text":"副总经理审核  ",  "loc":"510 40", "remark":""},
+    {"key":"7", "text":"总经理审核  ",  "loc":"500 180", "remark":""}
+  ],
+  "linkDataArray": [
+    {"from":"1", "to":"3"},
+    {"from":"3", "to":"4"},
+    {"from":"4", "to":"5"},
+    {"from":"5", "to":"2"},
+    {"from":"4", "to":"6", "key":"1001", "text":"小于5天 ", "remark":"", "condition":"Days<5"},
+    {"from":"6", "to":"5"},
+    {"from":"4", "to":"7", "key":"1002", "text":"大于5天 ", "remark":"", "condition":"Days>5"},
+    {"from":"7", "to":"5"}
+  ]}
\ No newline at file
diff --git a/business-behavior-monitor/docs/front/node_modules/@ant-design/icons/dist/ant-design-icons.css b/business-behavior-monitor