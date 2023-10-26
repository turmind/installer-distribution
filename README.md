# installer distribution

The installer distribution feature allows you to add download channel information to your installation packages. This can be useful for attributing data to specific distribution channels in the future. 

When users download and install your software from different sources - such as your website, a software repository, or an app store - you may want to track metrics separately for each channel. By embedding a unique identifier into the installer package, your app can report which distribution channel led to that install. 

This gives you visibility into the performance of various marketing channels in driving installations of your software. You can see which channels result in the most users, highest engagement, etc. With this data, you can focus your distribution efforts on the channels that deliver the best results.

The installer distribution configures a separate build of your installer for each channel. The channel identifier gets compiled into the installer binary itself. When users run the installer, your app can retrieve this identifier and attribute that install to the appropriate channel. This provides accurate tracking without any extra effort on the user side.
