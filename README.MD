```php
<?php

namespace App\Providers;

use Illuminate\Support\ServiceProvider;

final class NoelisTiredServiceProvider extends ServiceProvider
{
    public function register(): void
    {
        $this->app->singleton('NoelisTired', fn () => [
            'name' => 'Noel',
            'role' => 'Software Developer',
            'location' => 'The Netherlands',

            'education' => 'Fontys Hogeschool Tilburg',
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

<p align="center">
  <a href="https://discord.com/users/1090282176492339220">
    <img src="https://lanyard-profile-readme.vercel.app/api/1090282176492339220?theme=light&bg=809ecf&animated=false&hideDiscrim=true&borderRadius=30px&idleMessage=Probably%20doing%20something%20else..." alt="Discord Presence" />
  </a>
</p>
