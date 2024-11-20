# React-Components

<details>
    <summary>SVG + CSS Logo</summary>
<br/>
    <img src='./components/SVGLogo/Logo.svg' alt='DEV +CSS Logo' /><br/>

[SVG + CSS component](https://github.com/YashIsCursed/React-Components/components/SVGLogo/Logo.jsx)


### React Component
```jsx
export default function Logo() {
    return(
        <div className="logo">

            {/* Enter Yout Svg Code Here */}

        </div>
    )    
}
```


### Css Style

```css

.logo svg path{
  
    stroke:var(--fg);
    animation: Logo_Startup 2s ease-in-out forwards;
    stroke-width: 1;
    stroke-dashoffset: 0;

}

@keyframes Logo_Startup {
    0%{
        fill:transparent;
        stroke:var(--primary);
        stroke-dasharray: 10, 100;
    }80%{
        fill:transparent;
        stroke:var(--primary)

    }
    100%{
        fill:var(--fg);
        stroke-dasharray: 50,0;
    }
}
```



</details>