# PlaceholdUITextView
A customed UITextView with placeholder

自定义UITextView，可以在UITextView设置Placeholder

使用方法如下：

    PlaceholderTextView *textView = [[PlaceholderTextView alloc] initWithFrame:CGRectMake(50, 50, 200, 300)];
    [self.view addSubview:textView];
    textView.myPlaceholder = @"输入文字的asdasdasdasdsad...";
    textView.myPlaceholderColor = [UIColor lightGrayColor];



