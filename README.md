# FlowPageView
 flowView = [[FlowView alloc] initWithFrame:CGRectMake(0, 0, self.view.frame.size.width, self.view.frame.size.height  - self.navigationController.navigationBar.frame.size.height) imageArr:@[[UIImage imageNamed:@"676x676.jpg"],[UIImage imageNamed:@"676x676-2.jpg"]]];
    flowView.backgroundColor = [UIColor redColor];
    [self.view addSubview:flowView];
     以及实现代理方法即可.
     
     
     
     
     若有问题或者优化建议，欢迎咨询
