# php 基础知识

* Array 数组

        //自 PHP 5.4 起,新写法
        //普通数组
        $array = [ 'a', 'b', 'c' ];

        //关联数组
        $array = [
                "name" => "php" ,
                "var"  =>  5.6 ,
            ];
        ------------------
        ------------------
        //数组的大小
        count($array)

        //取索引(关联数组)
        array_keys($arr);

        //判断$key是否在$arr(普通数组)中
        in_array($key,$arr);

        //"普通数组"的遍历：
        for ( $arr as $val){
            //do something...
         }

        //关联数组的遍历：
        for ( $arr as $key => $val){
            //do something...
         }
        //检查给定的键名或索引是否存在于数组(关联数组)中
        //成功时返回 TRUE， 或者在失败时返回 FALSE。
        bool array_key_exists ( $key , $array)



