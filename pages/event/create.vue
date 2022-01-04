<template>
    <div>
        <h1>Create Event</h1>
    </div>
</template>
<script>
export default {
    name: 'EventCreate',
    head(){
        return {
        title: 'Event create', 
        meta: [{        
            hid: 'description',
            name: 'description',
            content: 'My Events create description'
        }]
        }
    }
}
</script>