<?php

namespace mathiaworms;

class About extends Me
{

    public function getDailyKnowledge(): array
    {
        return [
            C#::class,
            Ruby::class,
            HTML/CSS::class,
            Javascript::class,

        ];
    }

    public function getFutureGoal(): string
    {
        return 'Get More knowledge';
    }
}
>
