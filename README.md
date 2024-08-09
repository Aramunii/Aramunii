# Maer costa :man_technologist:

##### Work with

[![C#](https://img.shields.io/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?logo=lua&logoColor=white)](#)
[![PHP](https://img.shields.io/badge/php-%23777BB4.svg?&logo=php&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![Laravel](https://img.shields.io/badge/Laravel-%23FF2D20.svg?logo=laravel&logoColor=white)](#)
[![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?logo=node.js&logoColor=white)](#)
[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-%23313131.svg?logo=unrealengine&logoColor=white)](#)
[![Unity](https://img.shields.io/badge/Unity-%23000000.svg?logo=unity&logoColor=white)](#)

##### Social
[![Linkedin](https://img.shields.io/badge/LinkedIn-blue.svg?logo=Linkedin&logoWidth=20)](https://www.linkedin.com/in/warley-maer-costa-lacerda-3ba9b8166)
[![Instagram](https://img.shields.io/badge/Instagram-C13584.svg?logo=instagram&logoWidth=20&logoColor=white)](https://www.instagram.com/maercosta/)

```php
<?php

namespace MaerCosta;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Little Devil Inc',
                'position' => 'Game Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            ReactNative::class,
            NodeJS::class,
            LUA::class,
            C#::class,
            Unity::class,
            Unreal::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
