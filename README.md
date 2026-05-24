local NotificationLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/XcRNB/Notif/refs/heads/main/Notif"))()

NotificationLib.Success("标题", "绿色", 2)
NotificationLib.Error("失败", "红色", 2)
NotificationLib.Warning("注意", "黄色", 2)
NotificationLib.Info("提示", "蓝色", 2)

NotificationLib.Show("标题", "内容", 3, "gold", "purple")
