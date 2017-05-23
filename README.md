# SystemTabBarAnimation
系统tabbar的基础上点击tab添加的动画效果,提供思路
### 正常使用
      - (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {
      // Override point for customization after application launch.
      CustomTabBarController *tabbar = [[CustomTabBarController alloc]init];
      self.window.rootViewController = tabbar;
      return YES;
  }
  
  另:
  设置导航栏标题时:
      
      self.navigationItem.title = @"sbVc";
