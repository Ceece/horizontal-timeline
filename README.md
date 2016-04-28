# Horizontal Timeline

Like jQuery Tabs but Horizontal Timeline. powered by CSS3 and jQuery 1.7.2+.  
For demo, see http://ceece.github.io/horizontal-timeline  
For download, see https://github.com/Ceece/horizontal-timeline/releases

## Code Example

```html
<section id="timeline">
    <ul><!-- First list for events -->
        <li><a href="#" data-date="16/01/2014" class="selected">16/01/2014</a></li>
        <li><a href="#" data-date="28/02/2014">28/02/2014</a></li>
        ...
    </ul>
    <ul><!-- Second list for contents (option) -->
        <li data-date="16/01/2014">
            <h2>Horizontal Timeline</h2>
            <em>January 16th, 2014</em>
            <p> 
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod  
                tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,  
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo  
                consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse  
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non  
                proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  
            </p>
        </li>

        <li data-date="28/02/2014">
            <h2>Event title here</h2>
            <em>February 28th, 2014</em>
            <p> 
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod  
                tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,  
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo  
                consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse  
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non  
                proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  
            </p>
        </li>
        ...
</section>

<script type="text/javascript">
    $(document).ready(function() {
        $('#timeline').horizontalTimeline();
    });
</script>
```

## Options

    rotate             rotation of events (default: true)
    height             timeline's height in px (default: 100)
    distanceDay        distance of Day in px (default: 15)
    distanceWeek       distance of Week in px (default: 50)
    distanceMonth      distance of Month in px (default: 160)
    distanceYear       distance of Year in px (default: 500)
    maxDistanceTimes   max times of distance (default: 3)
    endlessStart       start timeline from endless (default: false)
    navToSlide         click nav arrow to slide (default: false)
    eventOffset        event offset before and after timeline in px (default: 60)