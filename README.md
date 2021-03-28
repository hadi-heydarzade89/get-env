# get-env
GetEnv is a magento 2 module
Get env.php on magento2


## How to use
`$_objectManager = Magento\Framework\App\ObjectManager::getInstance();`

`$getEnv = $objectManager->get(H2\GetEnv\Helper\GetEnv::class);`

You can call any method of GetEnv class