# flexyboard (in development)
> Super-flexible admin dashboard skeleton layout with Multisidebar, Fixed or scrollable Sidebar/Footer/Header, RTL, support

Creating a highly customizable layout is really tricky. 
We're creating this project as a base for creating configurable dashboard layouts.

## Technical requirements

- Left Sidebar
- Right Sidebar (optional)
- Header
- Footer
- Content
- RTL switch places of horizontal items, makes taxt-align to the right side
- Sidebars, Header, Footer can be fixed or scrollable
- Sidebars can be collabsed or exposed
- Sidebars might be hidden at certain screen widths
- Content can be fixed (e.g. bootstrap .container) or fluid
- Scrollable (non-fixed) sidebars can be sticked to content

## Install

```
npm i --save flexyboard
```

## Setup


### Default Layout

```
<div class="flexyboard">
  <div class="f-header">
    {your header content}
  </div>
  <div class="f-container">
    <aside class="f-sidebar">
       {your sidebar content}
    </div>
    <div class="f-content">
      {yout page content}
    </div>
    <div class="f-sidebar-secondary">
      {yout secondary sidebar content}
    </div>
  </div>
  <div class="f-footer">
    {your footer content}
  </div>
</div>
```

## Customization

ToDo


## ToDo

### Near-term

- Implement the lib
- Publish on NPM
- Default demo

### Mid-term

- Cover with tests
- Add UMD/CommonJS/ES modules support
- Add React component
- Add Angular2 component

### Long-term

- Demo pages with different UI frameworks
- Demo bootstrap
- Demo material
- Demo semantic-ui
- Demo zurb
- Demo facebook
