# OpenCart-Tools
Code with Mr Suraj

# https://chatgpt.com/canvas/shared/67c835860ae48191a04ecb6071742670


# blog path
catalog/view/theme/your-theme-name/template/extension/module/blog.twig


# Header Section me Link Add Karna
catalog/view/theme/your-theme-name/template/common/header.twig


# Product name edit
catalog/language/en-gb/product/product.php
$_['text_model'] = 'Product Code:';


# OpenCart me CSS Stylesheet ka Path
catalog/view/theme/default/stylesheet/stylesheet.css


# product card title name change or update or comment 
catalog/view/theme/YOUR_THEME/template/product/product.twig
{% if product_id == 42 %}
    <p>Brand:: {{ brand }}</p>
{% endif %}


# Custom Page (information - Remove Title from Page)
catalog/view/theme/your-theme-name/template/information/your-custom-page.twig


# Logo header path   ( <img src="{{ logo }}" alt="{{ name }}" /> )
/catalog/view/theme/YOUR_THEME_NAME/template/common/header.twig


# Product card me price .00 remove
Admin Panel me jao:
👉 System > Localisation > Currencies
Decimal places ko 2 se 0 me update karo.
