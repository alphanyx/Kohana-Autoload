## Kohana Autoloder Modul


With the Kohana Autoloader Modul is it possible to use Namespaces in Classes.

Example Call:
	
	$classLoader = new ClassLoader('Namespace\For\Class', PATH_TO_CLASSES);
	$classLoader->register();

With this setting, it is possible to load the Class 
	
	new \Namespace\For\Class\Test();
	
with just the shortcut
	
	new Test();


