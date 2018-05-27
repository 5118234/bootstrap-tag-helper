# Tabs

Tabs are a partial functionality of [Bootstrap Navs](https://getbootstrap.com/docs/4.0/components/navs/). The Bocons Tag Helper capsuled these pretty component to easy create tabbable regions.

<img class="img-shadow img-responsive center-block" src="https://raw.githubusercontent.com/brecons/bootstrap-tag-helper/master/docs/images/tabs_01.PNG" width="526" alt="Bootstrap Tabs">

```markup
<tabs>
    <tabs-pane bc-header="Home">
        <p>
            Consequat occaecat ullamco amet non eiusmod nostrud dolore ...
        </p>
    </tabs-pane>
    <tabs-pane bc-header="Profile">
        ...
    </tabs-pane>
    <tabs-pane bc-header="Settings">
        ...
    </tabs-pane>
</tabs>
```

## Tabs Configuration `<tabs>`

### Pills

Use the `bc-pills` attribute to render the tabs as pills.

<img class="img-shadow img-responsive center-block" src="https://raw.githubusercontent.com/brecons/bootstrap-tag-helper/master/docs/images/tabs_02.PNG" width="521" alt="Pills">

```markup
<tabs bc-pills="true">
    <tabs-pane bc-header="Home">
        ...
    </tabs-pane>
    <tabs-pane bc-header="Profile">
        ...
    </tabs-pane>
    <tabs-pane bc-header="Settings">
        ...
    </tabs-pane>
</tabs>
```

## Pane Configuration `<tabs-pane>`

### Header (Mandatory)

Use the `bc-header` attribute to define a title for the tab.

### Active

By default the first tab is active on page load. If you want to modify that, use the `bc-active` attribute to activate another tab on startup.

<img class="img-shadow img-responsive center-block" src="https://raw.githubusercontent.com/brecons/bootstrap-tag-helper/master/docs/images/tabs_03.PNG" width="551" alt="Active Tabs">

```markup
<tabs>
    <tabs-pane bc-header="Home">
        ...
    </tabs-pane>
    <tabs-pane bc-header="Profile" bc-active="true">
        ...
    </tabs-pane>
    <tabs-pane bc-header="Settings">
        ...
    </tabs-pane>
</tabs>
```