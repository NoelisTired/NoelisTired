```php
<?php

namespace App\Providers;

use Illuminate\Support\ServiceProvider;

final class BoyK07ServiceProvider extends ServiceProvider
{
    public function register(): void
    {
        $this->app->singleton('NoelisTired', fn () => [
            'name' => 'Noel',
            'role' => 'Software Developer',
            'location' => 'The Netherlands',

            'education' => 'Fonty's Hogeschool Tilburg',
            'work'      => 'Entrepreneur @ noelp.dev',

            'favorites' => [
                'languages' => ['PHP', 'Python', 'C#'],
                'framework' => 'Laravel',
            ],

            'contact' => [
                'email' => 'info@noelp.dev',
            ],
        ]);
    }
}
```

[![Discord Presence](https://lanyard-profile-readme.vercel.app/api/1090282176492339220?theme=light&bg=809ecf&animated=false&hideDiscrim=true&borderRadius=30px&idleMessage=Probably%20doing%20something%20else...)](https://discord.com/users/1090282176492339220)

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=noelistired&show_icons=true&locale=en&layout=compact" alt="noelistired" /></p>
