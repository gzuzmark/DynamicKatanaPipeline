# DynamicKatanaPipeline

[Example Katana style middleware](https://github.com/damianh/DynamicKatanaPipeline/blob/master/src/DynamicKatanaPipeline/DynamicKatanaMiddleware.cs) which contains one or more `Microsoft.Owin.StaticFiles` middleware that reconfigures itself based on changes to a config file based on a filesystem watcher.

Run the host project, edit the `config.txt` file (should be obvious) and refresh the page. 

Note: this isn't robust by any means.
