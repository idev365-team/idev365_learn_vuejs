<!-- 为什么要用组件？看下面的例子 -->

template=`
    <div>
        <search-bar search="search"/>
        <product-list ds="ds"/>
        <footer-bar />
    </div>
`

======================================================

template=`
    <div class="search-bar" >
        <input type="text" :value="search" />
        <button :click="search">Search</button>
    </div
    <div class="product-list" >
        <ul>
            <li v-for=""></li>
            .......
        </ul>
    </div>
    <div class="footer-bar">
        <span>{copyright}</span>
    </div>
`

