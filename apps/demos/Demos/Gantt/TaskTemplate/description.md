The DevExtreme Gantt templates help customize the layout and appearance of individual task elements. Templates allow you to mix HTML code with any DevExtreme JavaScript component - and position desired elements within the container. In this demo, a template is used to display images within tasks and change their background color.
<!--split-->

Implementation: Use the [taskContentTemplate](/Documentation/ApiReference/UI_Components/dxGantt/Configuration/#taskContentTemplate) template to customize and align task information within the template container. For each task, use the item property to obtain task information (title, resource, progress) and wrap it into div elements. Then, apply CSS styles to these div elements and place them into the container.
