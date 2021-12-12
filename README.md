# Maer costa :man_technologist:

[![NodeJS](https://img.shields.io/badge/NodeJS-Fan-FAC151.svg?logo=javascript&logoWidth=20)](https://github.com/aramunii)
[![PHP](https://img.shields.io/badge/Laravel-Fan-FAC151.svg?logo=laravel&logoWidth=20)](https://github.com/aramunii)
[![Npm](https://img.shields.io/badge/Npm-Newbie-FAC151.svg?logo=npm&logoWidth=20)](https://github.com/aramunii)
[![Npm](https://img.shields.io/badge/React%20Native-Newbie-FAC151.svg?logo=react&logoWidth=20)](https://github.com/aramunii)
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
                'company' => 'Support Health',
                'position' => 'Developer'         
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
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

