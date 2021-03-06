---
layout: default
title: The "textarea" control
slug: textarea
subtitle: Learn how to create controls using Kirki
mainMaxWidth: 55rem;
bodyClasses: control page
returns: string
heroButtons:
  - url: ../controls
    class: white button round border-only
    icon: fa fa-arrow-circle-o-left
    label: Back to Controls
---

`textarea` controls allow you to add a simple, multi-line text input.

### Example

```php
Kirki::add_field( 'theme_config_id', [
	'type'     => 'textarea',
	'settings' => 'my_setting',
	'label'    => esc_html__( 'Textarea Control', 'textdomain' ),
	'section'  => 'section_id',
	'default'  => esc_html__( 'This is a default value', 'textdomain' ),
	'priority' => 10,
] );
```
