# Yii2LottiePlayer

**Install**

    composer require jamshidbekakhlidinov/yii2-lottie-player


Ishlatilishi

    <?php

        echo LottiePlayer::widget([
            'src' => 'https://assets7.lottiefiles.com/packages/lf20_tmsiddoc.json',
            'options' => [
                'style' => [
                    'width' => '300px',
                ],
                'class' => 'justify-content-between'
            ]
        ])

    ?>