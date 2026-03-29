MVVM.ViewModel.Proxy.ExampleAvalonia

====================================

This is a demonstration of \[a ViewModel framework without backing fields](https://github.com/BruceMellows/MVVM.ViewModel.Proxy).



\*\*Ensure that you restore the git submodules prior to build\*\*

```

git submodule update --init --recursive --remote

```



This example just shows that property changes are propogated to the internal callback of your choice.



The `PropertyChanging` and `PropertyChanged` events are also fired.



In this simple example, the window title includes the dimensions of the window and changing the window dimension updates the window title.

