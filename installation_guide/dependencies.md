# Dependencies

## Installing Dependencies for the plugin

1. If you haven't downloaded OpenTabletDriver yet, you can follow the "installation" guides [here](https://opentabletdriver.net/). or in video format:

<section class="embed-container">
    <iframe src="https://www.youtube.com/embed/aFejLY4vKeY?si=7R3k1NKNmZKj2keB" title="YouTube video player" 
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <p>(Install .NET 6 Desktop Runtime if you plan to use OpenTabletDriver 0.6.4.0)</p>
</section>

2. Open `OpenTabletDriver.UX` and go to `Plugins` > `Open Plugin Manager`,
3. Look for `Enhanced Output Mode` in the list, select it and click `Install`,
4. Close the Plugin Manager,
5. Go to the `Tools` tab and select `Touch Toggle`,
6. Enable it & tick `Toggle Touch` to enable touch input.
7. Select `Touch Settings` & enable it.

```{admonition} For Wacom PTH-x60 Tablet (Paper Edition) Users Only
:class: warning
You will need to change the `MaxX` and `MaxY` values in the `Touch Settings` plugin. \
Follow the steps below to obtain these values.
```

8. Head to `Tablet` > `Tablet Debugger` and check your touch maxes there.
9. Move your finger slowly to the bottom right corner of the tablet and check the `X` and `Y` values.
10. Take note of these values and put them in the `Touch Settings` plugin.

## Installing Dependencies for the UX

1. Install the latest version of [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
2. You may want to open the terminal and run the following command:

```shell
dotnet --list-runtimes
```