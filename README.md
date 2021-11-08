# iOSSystemColor
iOS SystemColor

color vs systemColor:

Light vc Dark:

![image](https://github.com/xjh093/iOSSystemColor/blob/main/Screen%20Shot%202021-11-08%20at%203.44.05%20PM.png)


```
    NSArray *colors = @[
        [UIColor redColor],
        [UIColor systemRedColor],
        [UIColor greenColor],
        [UIColor systemGreenColor],
        [UIColor blueColor],
        [UIColor systemBlueColor],
        [UIColor orangeColor],
        [UIColor systemOrangeColor],
        [UIColor yellowColor],
        [UIColor systemYellowColor],
        [UIColor systemPinkColor],
        [UIColor systemTealColor],
        [UIColor systemGrayColor],
        [UIColor systemGray2Color],
        [UIColor systemGray3Color],
        [UIColor systemGray4Color],
        [UIColor systemGray5Color],
        [UIColor systemGray6Color],
    ];
    
    for (NSInteger i = 0; i < colors.count; i++) {
        CGFloat x = 90 * (i % 2);
        CGFloat y = 70 * (i / 2);
        UIView *view = [[UIView alloc] init];
        view.frame = CGRectMake(10 + x, 100 + y, 80, 60);
        view.backgroundColor = colors[i];
        [self.view addSubview:view];
    }
```
