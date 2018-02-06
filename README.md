This project exposes an issue with the SfNumericTextBox in iOS only.

The EditTest2Page.xaml file works fine in the previewer and on Android, but throws an exception in iOS :

```
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Xamarin.iOS.dll [External]
  Resolved pending breakpoint for 'UIKit.UIApplication.Main(string[], string, string)' to /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:61 [0x00000].
  Resolved pending breakpoint for 'UIKit.UIApplication.Main(string[], System.Type, System.Type)' to /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:68 [0x00000].
  Resolved pending breakpoint for 'UIKit.UIApplication.Main(string[])' to /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:73 [0x00000].
  Resolved pending breakpoint for 'UIKit.UIApplication.Main(string[], System.IntPtr, System.IntPtr)' to /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:78 [0x00000].
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.dll [External]
  Thread started:  #2
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/EditTest2.iOS.exe
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Xamarin.Forms.Platform.iOS.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Xamarin.Forms.Core.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Runtime.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.ObjectModel.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Core.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Mono.Security.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Xml.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.ComponentModel.Composition.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Collections.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Diagnostics.Debug.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Threading.Tasks.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Threading.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Globalization.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.ComponentModel.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Xml.ReaderWriter.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Reflection.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Linq.Expressions.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.IO.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Dynamic.Runtime.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Xamarin.Forms.Platform.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Runtime.Extensions.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Linq.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Reflection.Extensions.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Net.Http.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Runtime.Serialization.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.ServiceModel.Internals.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/EditTest2.dll
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/Xamarin.Forms.Xaml.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Text.RegularExpressions.dll [External]
  Loaded assembly: /Users/gary/Library/Developer/CoreSimulator/Devices/7C8C84E6-C3E7-401B-A804-1FB3DFCA587F/data/Containers/Bundle/Application/7E17EE92-ABBF-419E-B82F-6E0F9EE6B462/EditTest2.iOS.app/System.Diagnostics.Tools.dll [External]
  Loaded assembly: /Library/Frameworks/Xamarin.Interactive.framework/Versions/Current/Agents/Forms/iOS/Xamarin.Interactive.iOS.dll [External]
  Loaded assembly: /Library/Frameworks/Xamarin.Interactive.framework/Versions/Current/Agents/Forms/iOS/Xamarin.Interactive.dll [External]
  Loaded assembly: /Library/Frameworks/Xamarin.Interactive.framework/Versions/Current/Agents/Forms/iOS/netstandard.dll [External]
  2018-02-06 14:42:43.169 EditTest2.iOS[26642:3636512] 
  Unhandled Exception:
  Xamarin.Forms.Xaml.XamlParseException: Position 11:4. Type numeric:SfNumericTextBox not found in xmlns clr-namespace:Syncfusion.SfNumericTextBox.XForms;assembly=Syncfusion.SfNumericTextBox.XForms
    at Xamarin.Forms.Xaml.CreateValuesVisitor.Visit (Xamarin.Forms.Xaml.ElementNode node, Xamarin.Forms.Xaml.INode parentNode) [0x00040] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\CreateValuesVisitor.cs:48 
    at Xamarin.Forms.Xaml.ElementNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x000ab] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:149 
    at Xamarin.Forms.Xaml.ElementNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x00078] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:145 
    at Xamarin.Forms.Xaml.RootNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x00078] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:203 
    at Xamarin.Forms.Xaml.XamlLoader.Visit (Xamarin.Forms.Xaml.RootNode rootnode, Xamarin.Forms.Xaml.HydrationContext visitorContext) [0x00054] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:138 
    at Xamarin.Forms.Xaml.XamlLoader.Load (System.Object view, System.String xaml) [0x0004b] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:89 
    at Xamarin.Forms.Xaml.XamlLoader.Load (System.Object view, System.Type callingType) [0x0002f] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:68 
    at Xamarin.Forms.Xaml.Extensions.LoadFromXaml[TXaml] (TXaml view, System.Type callingType) [0x00000] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\ViewExtensions.cs:36 
    at EditTest2.EditTest2Page.InitializeComponent () [0x00001] in /Users/gary/temp/EditTest2/EditTest2/obj/Debug/EditTest2.EditTest2Page.xaml.g.cs:19 
    at EditTest2.EditTest2Page..ctor () [0x00008] in /Users/gary/temp/EditTest2/EditTest2/EditTest2Page.xaml.cs:9 
    at EditTest2.App..ctor () [0x0000f] in /Users/gary/temp/EditTest2/EditTest2/App.xaml.cs:11 
    at EditTest2.iOS.AppDelegate.FinishedLaunching (UIKit.UIApplication app, Foundation.NSDictionary options) [0x00007] in /Users/gary/temp/EditTest2/iOS/AppDelegate.cs:17 
    at (wrapper managed-to-native) UIKit.UIApplication:UIApplicationMain (int,string[],intptr,intptr)
    at UIKit.UIApplication.Main (System.String[] args, System.IntPtr principal, System.IntPtr delegate) [0x00005] in /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:79 
    at UIKit.UIApplication.Main (System.String[] args, System.String principalClassName, System.String delegateClassName) [0x00038] in /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:63 
    at EditTest2.iOS.Application.Main (System.String[] args) [0x00001] in /Users/gary/temp/EditTest2/iOS/Main.cs:17 
  2018-02-06 14:42:43.170 EditTest2.iOS[26642:3636512] Unhandled managed exception:
  Position 11:4. Type numeric:SfNumericTextBox not found in xmlns clr-namespace:Syncfusion.SfNumericTextBox.XForms;assembly=Syncfusion.SfNumericTextBox.XForms (Xamarin.Forms.Xaml.XamlParseException)
    at Xamarin.Forms.Xaml.CreateValuesVisitor.Visit (Xamarin.Forms.Xaml.ElementNode node, Xamarin.Forms.Xaml.INode parentNode) [0x00040] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\CreateValuesVisitor.cs:48 
    at Xamarin.Forms.Xaml.ElementNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x000ab] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:149 
    at Xamarin.Forms.Xaml.ElementNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x00078] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:145 
    at Xamarin.Forms.Xaml.RootNode.Accept (Xamarin.Forms.Xaml.IXamlNodeVisitor visitor, Xamarin.Forms.Xaml.INode parentNode) [0x00078] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlNode.cs:203 
    at Xamarin.Forms.Xaml.XamlLoader.Visit (Xamarin.Forms.Xaml.RootNode rootnode, Xamarin.Forms.Xaml.HydrationContext visitorContext) [0x00054] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:138 
    at Xamarin.Forms.Xaml.XamlLoader.Load (System.Object view, System.String xaml) [0x0004b] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:89 
    at Xamarin.Forms.Xaml.XamlLoader.Load (System.Object view, System.Type callingType) [0x0002f] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\XamlLoader.cs:68 
    at Xamarin.Forms.Xaml.Extensions.LoadFromXaml[TXaml] (TXaml view, System.Type callingType) [0x00000] in D:\agent\_work\1\s\Xamarin.Forms.Xaml\ViewExtensions.cs:36 
    at EditTest2.EditTest2Page.InitializeComponent () [0x00001] in /Users/gary/temp/EditTest2/EditTest2/obj/Debug/EditTest2.EditTest2Page.xaml.g.cs:19 
    at EditTest2.EditTest2Page..ctor () [0x00008] in /Users/gary/temp/EditTest2/EditTest2/EditTest2Page.xaml.cs:9 
    at EditTest2.App..ctor () [0x0000f] in /Users/gary/temp/EditTest2/EditTest2/App.xaml.cs:11 
    at EditTest2.iOS.AppDelegate.FinishedLaunching (UIKit.UIApplication app, Foundation.NSDictionary options) [0x00007] in /Users/gary/temp/EditTest2/iOS/AppDelegate.cs:17 
    at (wrapper managed-to-native) UIKit.UIApplication:UIApplicationMain (int,string[],intptr,intptr)
    at UIKit.UIApplication.Main (System.String[] args, System.IntPtr principal, System.IntPtr delegate) [0x00005] in /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:79 
    at UIKit.UIApplication.Main (System.String[] args, System.String principalClassName, System.String delegateClassName) [0x00038] in /Users/builder/data/lanes/5665/db807ec9/source/xamarin-macios/src/UIKit/UIApplication.cs:63 
    at EditTest2.iOS.Application.Main (System.String[] args) [0x00001] in /Users/gary/temp/EditTest2/iOS/Main.cs:17 
  2018-02-06 14:42:43.171 EditTest2.iOS[26642:3636512] critical: Stacktrace:

  2018-02-06 14:42:43.171 EditTest2.iOS[26642:3636512] critical: 
  Native stacktrace:

  2018-02-06 14:42:43.194 EditTest2.iOS[26642:3636512] critical: 	0   EditTest2.iOS                       0x000000010f79c874 mono_handle_native_crash + 244
  2018-02-06 14:42:43.194 EditTest2.iOS[26642:3636512] critical: 	1   libsystem_platform.dylib            0x000000011e759f5a _sigtramp + 26
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	2   libsystem_kernel.dylib              0x000000011e648480 libsystem_kernel.dylib + 1152
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	3   libsystem_c.dylib                   0x000000011e31e0eb abort + 127
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	4   EditTest2.iOS                       0x000000010f9657cf xamarin_unhandled_exception_handler + 47
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	5   EditTest2.iOS                       0x000000010f8074f4 mono_invoke_unhandled_exception_hook + 148
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	6   EditTest2.iOS                       0x000000010f79c39d mono_handle_exception_internal + 5805
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	7   EditTest2.iOS                       0x000000010f79ace8 mono_handle_exception + 24
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	8   EditTest2.iOS                       0x000000010f71d15f mono_amd64_throw_exception + 143
  2018-02-06 14:42:43.195 EditTest2.iOS[26642:3636512] critical: 	9   ???                                 0x000000013955dae7 0x0 + 5256895207
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	10  ???                                 0x000000013e445375 0x0 + 5339632501
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	11  ???                                 0x000000013e4451a3 0x0 + 5339632035
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	12  ???                                 0x000000013e42b613 0x0 + 5339526675
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	13  ???                                 0x000000013e42ac3d 0x0 + 5339524157
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	14  ???                                 0x000000013e03fc93 0x0 + 5335415955
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	15  EditTest2.iOS                       0x000000010f7ad929 mono_jit_runtime_invoke + 1273
  2018-02-06 14:42:43.196 EditTest2.iOS[26642:3636512] critical: 	16  EditTest2.iOS                       0x000000010f86d1d8 do_runtime_invoke + 88
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	17  EditTest2.iOS                       0x000000010f86d150 mono_runtime_invoke + 208
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	18  EditTest2.iOS                       0x000000010f96e54c xamarin_invoke_trampoline + 5996
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	19  EditTest2.iOS                       0x000000010f9763dd xamarin_arch_trampoline + 189
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	20  EditTest2.iOS                       0x000000010f977871 xamarin_x86_64_common_trampoline + 110
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	21  UIKit                               0x000000011409fbca -[UIApplication _handleDelegateCallbacksWithOptions:isSuspended:restoreState:] + 299
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	22  UIKit                               0x00000001140a1648 -[UIApplication _callInitializationDelegatesForMainScene:transitionContext:] + 4113
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	23  UIKit                               0x00000001140a6aeb -[UIApplication _runWithMainScene:transitionContext:completion:] + 1720
  2018-02-06 14:42:43.197 EditTest2.iOS[26642:3636512] critical: 	24  UIKit                               0x00000001144706f8 __111-[__UICanvasLifecycleMonitor_Compatability _scheduleFirstCommitForScene:transition:firstActivation:completion:]_block_invoke + 924
  2018-02-06 14:42:43.198 EditTest2.iOS[26642:3636512] critical: 	25  UIKit                               0x00000001148464c8 +[_UICanvas _enqueuePostSettingUpdateTransactionBlock:] + 153
  2018-02-06 14:42:43.198 EditTest2.iOS[26642:3636512] critical: 	26  UIKit                               0x00000001144702f1 -[__UICanvasLifecycleMonitor_Compatability _scheduleFirstCommitForScene:transition:firstActivation:completion:] + 249
  2018-02-06 14:42:43.198 EditTest2.iOS[26642:3636512] critical: 	27  UIKit                               0x0000000114470b6b -[__UICanvasLifecycleMonitor_Compatability activateEventsOnly:withContext:completion:] + 696
  2018-02-06 14:42:43.198 EditTest2.iOS[26642:3636512] critical: 	28  UIKit                               0x0000000114deea69 __82-[_UIApplicationCanvas _transitionLifecycleStateWithTransitionContext:completion:]_block_invoke + 262
  2018-02-06 14:42:43.198 EditTest2.iOS[26642:3636512] critical: 	29  UIKit                               0x0000000114dee922 -[_UIApplicationCanvas _transitionLifecycleStateWithTransitionContext:completion:] + 444
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	30  UIKit                               0x0000000114acb9c8 __125-[_UICanvasLifecycleSettingsDiffAction performActionsForCanvas:withUpdatedScene:settingsDiff:fromSettings:transitionContext:]_block_invoke + 221
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	31  UIKit                               0x0000000114ccab06 _performActionsWithDelayForTransitionContext + 100
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	32  UIKit                               0x0000000114acb88b -[_UICanvasLifecycleSettingsDiffAction performActionsForCanvas:withUpdatedScene:settingsDiff:fromSettings:transitionContext:] + 231
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	33  UIKit                               0x0000000114845b25 -[_UICanvas scene:didUpdateWithDiff:transitionContext:completion:] + 392
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	34  UIKit                               0x00000001140a536a -[UIApplication workspace:didCreateScene:withTransitionContext:completion:] + 523
  2018-02-06 14:42:43.199 EditTest2.iOS[26642:3636512] critical: 	35  UIKit                               0x0000000114680605 -[UIApplicationSceneClientAgent scene:didInitializeWithEvent:completion:] + 369
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	36  FrontBoardServices                  0x0000000122aa1cc0 -[FBSSceneImpl _didCreateWithTransitionContext:completion:] + 338
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	37  FrontBoardServices                  0x0000000122aaa7b5 __56-[FBSWorkspace client:handleCreateScene:withCompletion:]_block_invoke_2 + 235
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	38  libdispatch.dylib                   0x000000011e1d71ba _dispatch_client_callout + 8
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	39  libdispatch.dylib                   0x000000011e1dc468 _dispatch_block_invoke_direct + 324
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	40  FrontBoardServices                  0x0000000122ad6498 __FBSSERIALQUEUE_IS_CALLING_OUT_TO_A_BLOCK__ + 24
  2018-02-06 14:42:43.200 EditTest2.iOS[26642:3636512] critical: 	41  FrontBoardServices                  0x0000000122ad614e -[FBSSerialQueue _performNext] + 464
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	42  FrontBoardServices                  0x0000000122ad66bd -[FBSSerialQueue _performNextFromRunLoopSource] + 45
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	43  CoreFoundation                      0x000000010fff7101 __CFRUNLOOP_IS_CALLING_OUT_TO_A_SOURCE0_PERFORM_FUNCTION__ + 17
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	44  CoreFoundation                      0x0000000110096f71 __CFRunLoopDoSource0 + 81
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	45  CoreFoundation                      0x000000010ffdba19 __CFRunLoopDoSources0 + 185
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	46  CoreFoundation                      0x000000010ffdafff __CFRunLoopRun + 1279
  2018-02-06 14:42:43.201 EditTest2.iOS[26642:3636512] critical: 	47  CoreFoundation                      0x000000010ffda889 CFRunLoopRunSpecific + 409
  2018-02-06 14:42:43.202 EditTest2.iOS[26642:3636512] critical: 	48  GraphicsServices                    0x00000001211769c6 GSEventRunModal + 62
  2018-02-06 14:42:43.202 EditTest2.iOS[26642:3636512] critical: 	49  UIKit                               0x00000001140a85d6 UIApplicationMain + 159
  2018-02-06 14:42:43.202 EditTest2.iOS[26642:3636512] critical: 	50  ???                                 0x000000013d245ad8 0x0 + 5320760024
  2018-02-06 14:42:43.202 EditTest2.iOS[26642:3636512] critical: 	51  ???                                 0x000000013d245713 0x0 + 5320759059
  2018-02-06 14:42:43.202 EditTest2.iOS[26642:3636512] critical: 
  =================================================================
  Got a SIGABRT while executing native code. This usually indicates
  a fatal error in the mono runtime or one of the native libraries 
  used by your application.
  =================================================================
```
