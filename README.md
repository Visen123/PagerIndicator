# PagerIndicator
仿爱奇艺/腾讯视频ViewPager导航条实现，支持自定义导航条高度，宽度，颜色变化，字体大小变化。支持多种滚动模式，支持自定义每个TabView的样式。

一、如何引入DynamicPagerIndicator？

在app的build.gradle 添加:

	dependencies {
	        compile 'com.github.Visen123:PagerIndicator:V1.0'
	}
        
	
3.0以上gradle版本为：

	dependencies {
	        implementation 'com.github.Visen123:PagerIndicator:V1.0'
	}


布局配置此控件：

    <com.yanyiyun.mypagerindicatorlib.DynamicPagerIndicator
            android:id="@+id/dynamic_pager_indicator1"
            android:layout_width="match_parent"
            android:layout_height="48dp"
            app:indicatorLineScrollMode="dynamic"
            app:indicatorLineHeight="10dp"
            app:indicatorLineRadius="2dp"
            app:indicatorLineWidth="16dip"
            app:pagerIndicatorMode="scrollable_center"
            app:tabNormalTextColor="#999999"
            app:tabNormalTextSize="16sp"
            app:tabSelectedTextColor="#fff4ce46"
            app:tabSelectedTextSize="16sp"
            app:tabTextColorMode="gradient"/>
	    

        <android.support.v4.view.ViewPager
            android:id="@+id/view_pager1"
            android:layout_width="match_parent"
            android:layout_height="200dip"/>
	    
	    
          

