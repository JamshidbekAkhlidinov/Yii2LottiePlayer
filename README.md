# Yii2LottiePlayer

    <?php

        echo LottiePlayer::widget([
        'src' => Yii::getAlias('/lottie/not_found.json'),
        'options' => [
            'style' => [
                'width' => '300px',
            ],
            'class' => 'justify-content-between'
        ]
    ])

    ?>