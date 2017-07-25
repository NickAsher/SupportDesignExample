# SupportDesignExample

![demo gif](http://i.stack.imgur.com/qKeaF.gif)

This support design example deals gives three important Custom Implementaions of ViewPager, ListView and NestedScrollView . These classes are needed when you want to put ListView inside a ViewPager which is inside a ScrollView. The problem is that View within a ScrollView should have a fixed height. So we can't just do wrap_content on ViewPager. Also a fixed height cannot be given to ViewPager if it contains dynamic content like that from a listview. So We need custom implementations of these three classes. 
